# Tools List 

### Static Code and Metrics  Analyzers

| Tool Name             | Type                                                         | Link                                                         |
| --------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Coverity Scan         | Static Analyzer                                              | https://scan.coverity.com/                                   |
| PVS-Studio            | Bug Detection / Static Analyzer                              | https://pvs-studio.com/en/pvs-studio/                        |
| Cppcheck              | Static Analyzer                                              | https://cppcheck.sourceforge.io/                             |
| CppClean              | Static Analyzer                                              | https://github.com/myint/cppclean                            |
| CppDepend             | C/C++ Code Analyzer                                          | https://www.cppdepend.com/                                   |
| Flint / Flint++       | Analyze C++ code against Facebook's coding standards.        | https://github.com/facebookarchive/flint<br />https://github.com/JossWhittle/FlintPlusPlus |
| OCLint                | C, C++ and Objective-C code inspector                        | https://oclint.org/                                          |
| ReSharper C++ / CLion | Static Cdde Analyzer                                         | https://www.jetbrains.com/cpp/                               |
| IKOS                  | open source static analyzer, developed by NASA               | https://github.com/NASA-SW-VnV/ikos                          |
| Lizard                | Complexity Analysis Tool                                     | http://www.lizard.ws/                                        |
| metrix++              | collect and analyse code metrics                             | https://metrixplusplus.github.io/metrixplusplus/             |
| CNCC                  | Customizable Naming Convention Checker                       | https://github.com/mapbox/cncc                               |
| SourceMeter           | static source code analysis of C/C++, Java, C#, Python, and RPG projects | https://www.sourcemeter.com/                                 |
| Radon                 | Analyzes code for various metrics (lines of code, complexity, and so on) | https://radon.readthedocs.io/en/latest/                      |

### Code Coverage Tools

| Tool Name       | Type                     | Link                                               |
| --------------- | ------------------------ | -------------------------------------------------- |
| Codecov         | A coverage analysis tool | https://codecov.io/                                |
| Coveralls       | A coverage analysis tool | https://coveralls.io/                              |
| LCOV            | A coverage analysis tool | http://ltp.sourceforge.net/coverage/lcov.php       |
| Gcover          | A Coverage analysis tool | https://gcovr.com/en/stable/                       |
| OpenCppCoverage | A Coverage analysis tool | https://github.com/OpenCppCoverage/OpenCppCoverage |
|                 |                          |                                                    |
|                 |                          |                                                    |
|                 |                          |                                                    |
|                 |                          |                                                    |

###  Runtime Code Analyzers

| Tool Name              | Type                                                         | Link                                                         |
| ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Valgrind               | Runtime code analyzer that can detect memory leaks, race conditions, and other associated problems | https://valgrind.org/                                        |
| Dr Memory              | Runtime code analyzer that can detect memory leaks, race conditions, and other associated problems | https://drmemory.org/                                        |
| GCC / Clang Sanitizers | AddressSanitizer MemorySanitizer ThreadSanitizer UndefinedBehaviorSanitizer built into compilers | https://kristerw.blogspot.com/2018/06/useful-gcc-address-sanitizer-checks-not.html |
|                        |                                                              |                                                              |
|                        |                                                              |                                                              |
|                        |                                                              |                                                              |
|                        |                                                              |                                                              |
|                        |                                                              |                                                              |
|                        |                                                              |                                                              |

### Fuzzy Analyzers

> If your project accepts user defined input, considering running a fuzzy input tester. These tools use coverage reporting to find new code execution paths and try to breed novel inputs for your code. They can find crashes, hangs, and inputs you didn't know were considered valid.

| Tool Name          | Type                                                         | Link                                              |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------- |
| american fuzzy lop | Fuzzy Analyzer                                               | http://lcamtuf.coredump.cx/afl/                   |
| LibFuzzer          | Fuzzy Enngine                                                | https://llvm.org/docs/LibFuzzer.html              |
| Klee               | fuzz individual functions                                    | http://klee.github.io/                            |
| Atheris            | A Coverage-Guided, Native Python Fuzzer                      | https://pypi.org/project/atheris/                 |
| Jazzer             | Jazzer is a coverage-guided, in-process fuzzer for the JVM platform | https://github.com/CodeIntelligenceTesting/jazzer |
| Sharpfuzz          | fuzz to .NET platform                                        | https://mijailovic.net/2019/01/03/sharpfuzz/      |
|                    |                                                              |                                                   |
|                    |                                                              |                                                   |
|                    |                                                              |                                                   |

### Testing 

| Tool Name   | Type                | Link                                             |
| ----------- | ------------------- | ------------------------------------------------ |
| Google Test | Unit Test Framework | https://github.com/google/googletest             |
| Catch       | Unit Test Framework | https://github.com/philsquared/Catch             |
| CPPUtest    | Unit Test Framework | https://github.com/cpputest/cpputest             |
| Boost.test  | Unit Test Framework | http://www.boost.org/doc/libs/release/libs/test/ |
|             |                     |                                                  |
|             |                     |                                                  |
|             |                     |                                                  |
|             |                     |                                                  |
|             |                     |                                                  |

### Mutation Testers

> These tools take code executed during unit test runs and mutate the executed code. If the test continues to pass with a mutation in place, then there is likely a flawed test in your suite

| Tool Name      | Type                        | Link                                                         |
| -------------- | --------------------------- | ------------------------------------------------------------ |
| Dextool Mutate | Mutation Testing            | https://github.com/joakim-brannstrom/dextool/tree/master/plugin/mutate |
| MuCPP          | Mutation Testing            | https://neptuno.uca.es/redmine/projects/mucpp-mutation-tool/wiki |
| Mull           | Mutation Testing            | https://github.com/mull-project/mull                         |
| CCMutator      | Mutation Testing            | https://github.com/markus-kusano/CCMutator                   |
| mutmut         | Python Mutation testing     | https://pypi.org/project/mutmut/                             |
| pitest         | Java Mutation tetsing       | https://pitest.org/                                          |
| StrykerJS      | JavaScript Mutation testing | https://stryker-mutator.io/                                  |
| stryker-net    | Dotnet Mutation testing     | https://stryker-mutator.io/docs/stryker-net/getting-started  |
|                |                             |                                                              |

### Debugging Helpersb

| Tool Name | Type                                                         | Link                                |
| --------- | ------------------------------------------------------------ | ----------------------------------- |
| uftrace   | Generates function call graphs of a program execution        | https://github.com/namhyung/uftrace |
| rr        | A lightweight tool for recording, replaying and debugging execution of applications | https://rr-project.org/             |
|           |                                                              |                                     |
|           |                                                              |                                     |
|           |                                                              |                                     |
|           |                                                              |                                     |
|           |                                                              |                                     |
|           |                                                              |                                     |
|           |                                                              |                                     |

