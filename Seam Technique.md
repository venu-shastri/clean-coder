### Seam Technique

---

#### Object Seam



```c++
bool CAsyncSslRec::Init()
{
	if (m_bSslInitialized) {
		return true;
	}
	m_smutex.Unlock();
	m_nSslRefCount++;
	m_bSslInitialized = true;
	FreeLibrary(m_hSslDll1);
	m_hSslDll1=0;
	FreeLibrary(m_hSslDll2);
	m_hSslDll2=0;
	if (!m_bFailureSent) {
		m_bFailureSent=TRUE;
		//global function that communicates with another subsystem, and that subsystem is a pain to work 			with under test
		PostReceiveError(SOCKETCALLBACK, SSL_FAILURE);
	}
	CreateLibrary(m_hSslDll1,”syncesel1.dll”);
	CreateLibrary(m_hSslDll2,”syncesel2.dll”);
	m_hSslDll1->Init();
	m_hSslDll2->Init();
	return true;
}


How do we execute the method without calling PostReceiveError under test? How do we do that and still allow the call to PostReceiveError in production?

//Object Seam (Available in Object Oriented languages)

class CAsyncSslRec
{
...
virtual void PostReceiveError(UINT type, UINT errorcode);
...
};
void CAsyncSslRec::PostReceiveError(UINT type, UINT errorcode)
{
//Calling the global function
::PostReceiveError(type, errorcode);
}


class TestingAsyncSslRec : public CAsyncSslRec
{
	virtual void PostReceiveError(UINT type, UINT errorcode)
	{
			//nulled out the behavior of the call to PostReceiveError
	}
}



```

#### Preprocessing Seam

---

```C++

#include <DFHLItem.h>
#include <DHLSRecord.h>

extern int db_update(int, struct DFHLItem *);

void account_update(int account_no, struct DHLSRecord *record, int activated)
	{
		if (activated) {
			if (record->dateStamped && record->quantity > MAX_ITEMS) {
				db_update(account_no, record->item);
			}
            else {
					db_update(account_no, record->backup_item);
				 }
			}
		db_update(MASTER_ACCOUNT, record->item);
	}
Preprocessing seams to replace the calls to db_update

localdefs.h
-----------------------------------------------------------------------------------------------------------
#ifdef TESTING
...
struct DFHLItem *last_item = NULL;
int last_account_no = -1;
#define db_update(account_no,item)
{last_item = (item); last_account_no = (account_no);}
...
#endif
----------------------------------------------------------------------------------------------------------


#include <DFHLItem.h>
#include <DHLSRecord.h>
extern int db_update(int, struct DFHLItem *);

#include "localdefs.h" //seam support

void account_update(int account_no, struct DHLSRecord *record, int activated)
	{
		if (activated) {
			if (record->dateStamped && record->quantity > MAX_ITEMS) {
				db_update(account_no, record->item);
			}
            else {
					db_update(account_no, record->backup_item);
				 }
			}
		db_update(MASTER_ACCOUNT, record->item);
	}
```



#### Link Seam

---

```
package fitnesse;
import fit.Parse;
import fit.Fixture;
import java.io.*;
import java.util.Date;
import java.io.*;
import java.util.*;
public class FitFilter {
	public String input;
	public Parse tables;
	public Fixture fixture = new Fixture();
	public PrintWriter output;
	public static void main (String argv[]) {
			new FitFilter().run(argv);
	}
	public void run (String argv[]) {
			args(argv);
			process();
			exit();
	}
	public void process() {
		try {
			tables = new Parse(input);
			fixture.doTables(tables);
		} catch (Exception e) {
				exception(e);
		}
		tables.print(output);
	}
...
}
In this file, we import fit.Parse and fit.Fixture. How do the compiler and the JVM find those classes? In Java, you can use a classpath environment variable to determine where the Java system looks to find those classes

create classes with the same names, put them into a different directory, and alter the classpath to link to a different fit.Parse and fit.Fixture

Many C and C++ build systems perform static linking to create executables. Often the easiest way to use the link seam is to create a separate library for any classes or functions you want to replace. When you do that, you can alter your build scripts to link to those rather than the production ones when you are testing.
```

