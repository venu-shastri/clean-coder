## Rules and Principles for Coding (Behavior , Attitude , mood while writing code)

- **Roots of  confidence and error-sense.**

  - mental, moral, and emotional context for writing code

- **Readiness**

  - Coding is an intellectually challenging and exhausting activity. It requires a level
    of concentration and focus
  - Code must work
    - Consider  all the warts of the current system
      - Problem , platform , Current Architecture ,  Language
  - Code must fit well into the existing system
    - Code should not increase the rigidity, fragility, or opacity of that system
    - Dependencies must be well-mannered
  - Code must be readable by other programmers
    - Most difficult thing a programmer can master
  - Opportunity for **distraction** is high
    - It is physiologically difficult to maintain the necessary concentration and focus for long periods of time
    - The cares and concerns of everyday life, as well as the issues and distractions of working as a team member , in an organization
    - "Working while distracted creates waste"
    - If you are **tired** or **distracted**, **do not code**
  - **Early Morning Code or Late Night Code** 
    - Developers typically feel good about themselves because of the long hours they work and how dedicated they are.
      - “Look out! Your about to send mail to Yourself"
      - Don’t write code when you are tired. Dedication and professionalism are more about discipline than hours
  - **WORRY CODE**
    - Have you ever gotten into a big fight with your spouse or friend, and then tried to code?
    - Did you notice that there was a background process running in your mind trying to resolve, or at least review the fight
    - Concentration waves
    - Catatonic and Paralyzed.
      - Find Yourself with your  eyes on the screen and my fingers on the keyboard, doing nothing
      - A million miles away working through the problem in the background rather than actually solving the coding problem in front of me.
      - When you think this is no time to code. Any code you produce will be trash. So instead of coding, you  need to resolve the worry.
      - Learn how to shut down the background process, or at least reduce its priority so that it’s not a continuous distraction
      - Professional developers allocate their personal time in order to ensure that the time spent at the office is
        as productive as possible
        - Professional developers allocate their personal time in order to ensure that the time spent at the office is
          as productive as possible
  - **The Flow Zone**
    - Hyper-productive state known as “flow.”
    - Highly focused, tunnel-vision state of consciousness that programmers can get into while they write code
    - In this state they feel productive. In this state they feel perfect
    - Avoid the Zone.
      - This state of consciousness isn't particularly productive, and it's far from perfect. It's essentially a light meditative state in which certain cognitive abilities are weakened in favour of a sense of speed.
      - The problem is that developer will  lose some of the big picture while they  are in the Zone, so developer  will likely make decisions that you will later have to go back and reverse. Code written in the Zone may come out faster, but you will  be going back to visit it more.
    - How to avoid slipping into the Zone,
      - take  a break
      - walk away for a few minutes
      - Clear head by answering a few emails or looking at some tweets
      - If its noon , take a lunch break
      - If your  working on a team, I’ll find a pair partner.
      - Pair programming
        - The **Zone** is an **uncommunicative state**, while **pairing** requires **intense and constant communication**
  - Writers Block
    - Sometime code refuses to appear.
    - Find a pair partner
      - There is a physiological change that takes place when you work with someone results in melting of blockage
    - creative output depends on creative input.
      - creativity breeds creativity
    - **Debugging Time** 
      - debugging time as a call of nature, something that just has to be done.
      - debugging time is just as expensive to the business as coding time is, and therefore anything we can do to avoid or diminish it is good
      - Radical reduction in debugging time by adopting the practice of Test
        Driven Development (TDD)

  #### PAC I N G YOURSELF

  ##### KNOW WHEN TO WALK AWAY

  - Can’t go home till you solve this problem ?
    - When you are stuck, when you are tired, disengage for awhile. Give your creative subconscious a crack at the problem

  ##### BEING LAT E

  - Sometimes we just blow our estimates and wind up late.
  - How to manage Lateness
    - Early detection and transparency
    - The worst case scenario occurs when you continue to tell everyone, up to the very end,
      that you will be on time—and then let them all down
    - Instead, regularly measure your progress against your goal, and come up with three4
      fact-based end dates: best case, nominal case, and worst case
    - Do not incorporate hope into your estimates
    - Present all three numbers to your team and stakeholders. Update these numbers daily

  ##### HOPE

  What if these numbers show that you might miss a deadline?

  Hope is the project killer. Hope destroys schedules and ruins reputations. Hope will get you into deep
  trouble.

  

  ##### RUSHING

  - What if your manager sits you down and asks you to try to make the deadline?
  - “do what it takes”?
  - Do not be tempted to rush.
  - Tell your boss that you’ve already considered the options (because you have) and that the only way to improve the schedule is to reduce scope.

  

  ##### FALSE DELIVERY

  -  Saying you are done when you know you aren’t
  - We convince ourselves that we are done enough, and move on to the next task. We rationalize that any work that remains can be dealt with later when we have more time
  - One of my clients actually defined “done” as “checked-in.” The code didn’t even have to compile.

  ##### DEFINE “DONE ”

  - Have your business analysts and testers create automated acceptance tests5 that must pass before you can say that you
    are done.

  

  ### TDD

  ---

  - TDD is the professional option. It is a discipline that enhances certainty, courage, defect reduction, documentation, and design
  - Test First Programming
  - Cycle Time 
  - How can you get automated unit tests with very high coverage without practicing TDD?
  - THE THREE LAW S OF TDD
    - You are not allowed to write any production code until you have first written a failing unit test.
    - You are not allowed to write more of a unit test than is sufficient to fail—and not compiling is failing
    - You are not allowed to write more production code that is sufficient to pass the currently failing unit test
  - Benefits
    - If you adopt TDD as a professional discipline, then you will write dozens of
      tests every day, hundreds of tests every week, and thousands of tests every year.
      And you will keep all those tests on hand and run them any time you make any
      changes to the code
    - Whenever you make a change to any part of Code, You simply run the unit tests. If
      they pass, then you nearly certain that the change you made didn’t break anything.
      How certain is “nearly certain”? Certain enough to ship!
    - Reduced Defect Injection Rate
    - Courage
      - “This is a mess, it needs to be cleaned"
      - “I’m not touching it!” Why? Because you know that if you touch it you risk breaking it; and if you break it, it becomes yours.
      - How to be sure that your cleaning did not break anything
      - When you have a suite of tests that you trust, then you lose all fear of making changes
    - Documentation
      - The unit tests are documents. They describe the lowest-level design of the system.
    - Design
      - Tests you write after the fact are defense. The tests you write first are offense
  - No professional developer should ever follow a discipline when that discipline does
    more harm than good
  - if you write your tests first. Indeed, you can write bad tests.

  

  

  ### Practicing

  ----

  

  - speed depends on practice
  - Use Programming Kata
    - A programming kata is a precise set of choreographed keystrokes and mouse movements that simulates the solving of some programming problem. You aren’t actually solving the problem because you already know the solution.
      Rather, you are practicing the movements and decisions involved in solving the problem.
    - [Code Kata: Archive (softwarecraftsmanship.org)](https://katas.softwarecraftsmanship.org/archive)
    - http://codekata.pragprog.com.
  - Use Wasa
    - Wasa is very much like a two-man kata. The routines are precisely memorized and played back. One partner plays the role of the aggressor, and the other partner is the defender. The motions are repeated over and over again as the
      practitioners swap roles.
    - One programmer writes a unit test, and then the other must make it pass. Then they reverse
      roles.  
    - [Pair Programming Ping Pong Pattern (c2.com)](http://wiki.c2.com/?PairProgrammingPingPongPattern)
    - For example, if the programmers choose to  implement a sort algorithm, the test writer can easily put constraints on speed and memory space that will challenge his partner. This can make the game quite competitive . . . and fun.

  

  #### BROADENING YOUR EXPERIENCE

  - Professional programmers often suffer from a lack of diversity in the kinds of problems that they solve.

  - Employers often enforce a single language, platform, and domain in which their programmers must work

  - Problems

    - lead to a very unhealthy narrowing of Developer resume and mindset
    - Such programmers to find themselves unprepared for the changes that periodically sweep the industry.

  - How to stay ahead of the curve

    - Open Source Project : Take on some pro-bono work by contributing to an open-source project.
    - PRACTICE ETHICS  
      - Professional programmers practice on their own time
        - It is not your employer’ job to help you keep your skills sharp for you
        - Employers of programmers don’t have to pay you for your practice time

    

    

  

  ### Communicating Requirements

  - The role of the professional developer is a communications role as well as a development
    role.
  - Common communication issues between programmers and business is the requirements
  - **PREMATURE PRECISION**
    - Business people want to know exactly what they are going to get before they authorize a project
    - Developers want to know exactly what they are supposed to deliver before they estimate the project
  - **Observer effect or The Uncertainty Principle**
    - The problem is that things appear different on paper than they do in a working system.
    - When you demonstrate a feature to the business, it gives them more information than they had before, and that new information impacts how they see the whole system.
  - **Estimation Anxiety**
    - The requirements will change making that precision moot.
    - Professional developers understand that estimates can, and should, be mad based on low precision requirements, and recognize that those estimates are estimates. To reinforce this, professional developers always include error bars with their estimates so that the business understands the uncertainty
  - **LAT E AMBIGUITY**
    - Professional programmers don't fill out a requirement until they're about to implement it.
    - “An ambiguity in a requirements document represents an argument amongst the stakeholders
    - Sometimes the stakeholders simply assume that their readers know what they mean , It may be perfectly clear to them in their context, but mean something completely different to the programmer who reads it results in Contextual Ambiguity
  - The only way  to effectively eliminate communication errors between programmers and stakeholders is to write automated acceptance tests

  #### ACCEPTANCE TESTS

  Myths

  - These are the tests that users execute before they accept a release.
  -  These are QA tests. 

  Facts

  - Tests written by a collaboration of the stakeholders and the programmers in order to define when a requirement is **done**
  - Acceptance tests should always be automated
  - Automated tests will prevent you from implementing the wrong system and will allow you to know when you are done.
  - Automated test specification  are the perfect requirements document

  **THE DEFINITION OF “DONE ”**

  - Is the developer done in the sense that he’s ready to deploy the feature with full confidence?
  - Does he mean that he’s ready for QA
  - perhaps he’s done writing it and has gotten it to run once but hasn’t really tested it yet.
  - "complete ,done , done-done"
  - Done means all code written, all tests pass, QA and the stakeholders have accepted. Done
  - Professional developers drive the definition of their requirements all the way to automated acceptance tests

  #####  WHO WRITES ACCEPTANCE TESTS , AND WHEN ?

  - stakeholders and QA would collaborate to write these tests and  developers would review them for consistency.
  - Business analysts write the “happy path” versions of the tests, because those tests describe the features that have business value
  - QA typically writes the “unhappy path” tests, the boundary conditions, exceptions, and corner cases. This is because QA’s job is to help think about what can go wrong.
  - “late precision"
    - Acceptance tests should be written as late as possible, typically a few days before the feature is implemented
    - In Agile projects, the tests are written after the features have been selected for the next
      Iteration or Sprint
  - Developer’s job to connect the acceptance tests to the system, and then to make those tests pass.

  #####  TEST NEGOTIATION AND PASSIVE AGGRESSION

  - Test authors are human and make mistakes (complicated, awkward , contains silly assumptions , May be Wrong)
  - As a professional developer, it is your job to negotiate with the test author for a better test.
  - Never do is take the passive-aggressive option and say to yourself, “Well, that’s what the test says, so that’s what I’m going to do.”

  ##### Acceptance  Test v/s Unit Test

  | Acceptance Test                                              | Unit Test                                                    |
  | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | Acceptance tests are written by the business for the business | Unit tests are written by programmers for programmers        |
  | They are formal requirements documents that specify how the system should behave from the business’ point of view | They are formal design documents that describe the lowest level structure and behavior of the code |
  | Audience is the business and the programmers                 | The audience is programmers, not business                    |
  | Acceptance tests invoke the system much farther out, at the API or sometimes even UI level | Unit tests dig into the guts of the system making< calls to methods in particular classes. |

  ​	Make sure that all your unit tests and acceptance tests are run several times per day in a continuous integration system.



#### Testing Strategy

---

**Write Requirements In Code**

> Requirements documents often become big, unreadable, ambiguous, unmaintainable messes in the way that other [BigDesignUpFront](http://wiki.c2.com/?BigDesignUpFront) artifacts do. So, some developers believe that instead of creating such a document, it is better to express requirements in code:
>
> 1. Before implementation, requirements can be expressed as [UnitTest](http://wiki.c2.com/?UnitTest)s and automated [AcceptanceTest](http://wiki.c2.com/?AcceptanceTest)s.





## Time Management

- Meetings

  - Two truths 
  - Meetings Are Necessary
  - Meetings Are Huge  time wasters
  - Actively resist attending meetings that don’t have an immediate and significant benefit.
  - Professionals are aware of the high cost of meetings

- DECLINING

  - Person inviting you to a meeting is not responsible for managing your time.
  - don’t accept unless it is a meeting for which your participation is immediately and significantly necessary to the job you are doing now.
  - Sometimes the meeting will be about something that interests you, but is not immediately necessary
  - Sometimes the meeting will be about something that you can contribute to but is not immediately significant to what you are currently doing
  - Sometimes your presence at the meeting will be requested by someone in authority (You will have to choose whether that authority outweighs your work schedule)
  - One of the most important duties of your manager is to keep you out of meetings.

- HAV E AN AGENDA AND A GOAL

  - clear agenda, with times for each topic and a stated goal

- STA N D - UP MEETINGS

  - What did I do yesterday?
  - What am I going to do today?
  - What’s in my way?
  - Each question should require no more than twenty seconds
  - Each participant should require no more than one minute

- ITER ATION PLANNING MEETINGS

  - select the backlog items that will be executed in the next iteration
  - acceptance/component tests will already be written, or at least sketched out
  - Meeting should take no more than 5% of the total time in the iteration
  - One week iteration (forty hours) the meeting should be over within two hours.

- ITER ATION RESTROSPECTIVE AND DEMO

  - Conducted at the end of each iteration
  - Members discuss what went right and what went wrong.
  - no more than 20 minutes for retrospective and 25 minutes for the demo

- ARGUMENTS /DI SAGREEMENTS

  - ​	“Any argument that can’t be settled in five minutes can’t be settled by arguing.”
  -    "win an argument by force of character"
  - "passive-aggressive" - "They’ll agree just to end the argument"
  - Without data, any argument that doesn’t forge agreement within a few minutes simply won’t ever forge agreement.
  - How do you get the data you need to settle a disagreement
    - run experiments, or do some simulation or modeling

- Manage time and focus

  - TIME BOXI N G AND TOMATOES
    - http://www.pomodorotechnique.com/

- AVO I DA N C E

  - Priority inversion
    - You raise the priority of a task so that you can postpone the task that has the true priority.
    - Priority inversions are a lie we tell ourselves
    - We can’t face what needs to be done.
    - Professionals prioritise tasks based on their importance, ignoring their personal fears and wishes, and do them in that order.

- BLIND ALLEYS

  - You'll occasionally make a decision and follow a technical path that leads nowhere. The more invested you are in your choice, the longer you will be lost in the woods.
  - Prudence and experience will help you avoid certain blind alleys.
  - real skill you need is to quickly realize when you are in one, and have the courage to back out
  - The Rule of Holes: When you are in one, stop digging.

- Mess

  - At some point you realize that you made a wrong design choice when you started, and that your code doesn’t scale well in the direction that the requirements are moving.
  - inflection point!
    - You can still go back and fix the design. But you can also continue to go forward. Going back looks expensive because you’ll have to rework the existing code, but going back will never be easier than it is now. If you go forward you will drive the system into a swamp from which it may never escape.

- LEAVING

  - When the meeting gets boring, leave

  - not storm out of a meeting exclaiming “This is boring!”

    - if your presence is still necessary

    - can’t afford a lot more time

    - expedite the discussion or shuffle the agenda

      

  

### WHAT IS AN ESTIMATE ?

---

- Business likes to view estimates as commitments

- Developers like to view estimates as guesses

- Commitment

  - A commitment is something you must achieve
  - Professionals don’t make commitments unless they know they can achieve them
  - Commitment is about certainty.
    - Other people are going to accept your commitments and make plans based upon them.

- An estimate is a guess.

  -  No commitment is implied. No promise is made.
  - we don’t know how long something will take.

- Unfortunately, most software developers are terrible estimators

  - An estimate is not a number. An estimate is a distribution
  - Professionals draw a clear distinction between estimates and commitments.
  - not to make any implied commitments

- PERT (Program Evaluation and Review Technique (PERT)

  - Way to convert estimates into probability distributions suitable for managers

  - When you estimate a task, you provide three numbers. This is called trivariate analysis:

    - O: Optimistic Estimate
      - This number is wildly optimistic. You could only get the task done this quickly if absolutely everything went right. Indeed, in order for the math to work this number should have much less than a 1% chance of occurrence.2 In Peter’s case, this would be 1 day
    - N: Nominal Estimate
      - This is the estimate with the greatest chance of success. If you were to draw a bar chart, it would be the highest bar, as shown in Figure 10-1. It is 3 days.
    - P: Pessimistic Estimate.
      - P: Pessimistic Estimate. Once again this is wildly pessimistic. It should include everything except hurricanes, nuclear war, stray black holes, and other catastrophes. Again, the math only works if this number has much less
        than a 1% chance of success. In Peter’s case this number is off the chart on the right. So 12 days.
      - μ =O+ 4N + P / 6
      - SD=P-O/6

    - WIDEBAND DELPHI
      - A team of people assemble, discuss a task, estimate the task, and iterate the discussion and estimation until they reach agreement.
      - Others can see things that you don’t
      - Flying Fingers
      - Planning Poker
        - planningpoker.com
        - https://store.mountaingoatsoftware.com/products/planning-poker-cards
      - Affinity Estimation
    - THE LAW OF LARGE NUMBERS
      - Estimates are fraught with error. That’s why they are called estimates
      - An implication of this law is that if you break up a large task into many smaller tasks and estimate
        them independently, the sum of the estimates of the small tasks will be more accurate than a single estimate of the larger task. The reason for this increase in accuracy is that the errors in the small tasks tend to integrate out.
      - http://en.wikipedia.org/wiki/Law_of_large_numbers

    

    

    

    









## what it means to be a Professional Programmer



- Attitude 
- Disciplined
- Actions

>  “I am a professional!” 



### Professionalism 

---

- Badge of Honor and Pride

- Marker of Responsibility and Accountability

- Non Professional 

  - “stuff happens”
  - shoulders shrugged

  > A nonprofessional makes an error, the employer cleans up the mess. But when a professional makes a mistake, he cleans up the mess

###  Taking Responsibility



- professionalism is all about taking responsibility

  > we must not create bugs - Software is too complex to create without bugs.-
  >
  > The human body is too complex to understand in it’s entirety, but doctors still take an oath to do no harm

- Developers must be responsible for their  imperfections

- The fact that the task to write perfect software is virtually impossible does not mean you aren’t responsible for the imperfection.

- Developers must practice is apologizing. Apologies are necessary, but insufficient

- Avoid making the same errors over and over.

- As Developer mature in profession, Developer error rate should rapidly decrease towards the asymptote of zero

### Quality Analyst Should Find Nothing

- Nothing should be discovered by a quality analyst.

- It is unprofessional in the extreme to purposely send code that you know to be faulty to QA

- To purposefully send code to QA that you know is erroneous is quite unprofessional.

  > Faulty Code ? - Any code Developers unsure about!

- Is QA used by developers to catch bugs?

  - QA is responsible for finding bugs and reporting them to the developers. Some companies do, in fact, pay QAs based on the number of defects they uncover.
  - This is a costly activity that harms the organization and the product by disrupting schedules and eroding the enterprise's faith in the development team. This is just plain reckless and lazy behavior
  - It's unprofessional to release code to QA that you don't know works. It goes against the "do no harm" principle..

- Developers should be astonished, chastened, and driven to prevent a problem from occurring again every time QA, or worse, a user, discovers one.



#### Saying "No"

----

- Professionals speak truth to power. Professionals have the courage to say no to their managers.
- How do you say no to your boss? After all, it’s your boss! Aren’t you supposed to do what your boss says?
- professionals are expected to say no
- Managers job is to pursue and defend their objectives as aggressively as they can
- Developers professionals they will pursue and defend their objectives as aggressively as they can.
- When your manager tells you that the login page has to be ready by tomorrow, he is pursuing and defending one of his objectives. He’s doing his job. If you  know full well that getting the login page done by tomorrow is impossible, then
  you are not doing your job if you say “OK, I’ll try.” The only way to do your job, at that point, is to say “No, that’s impossible.
- your manager is counting on you to defend your objectives as aggressively as he defends his
- seek for the best possible outcome
- The best possible outcome is the goal that you and your manager share. he trick is to find that goal, and that usually takes negotiation.
- “Is good code impossible? Is professionalism impossible?”

#### Saying "Yes" - A LANGUAGE OF COMMITMENT

---

There are three parts to making a commitment

- You say you’ll do it.
- You Mean it
- You  actually Do It



>There are very few people who, when they say something, they mean it and then actually get it done
>
>There are some who will say things and mean them, but they never get it done.
>
>There are far more people who promise things and don’t even mean to do them
>
>intuition can fail us
>
>trusting our guts



**RECOGNIZING LAC K OF COMMITMENT**

- Need\should. “We need to get this done.” “I need to lose weight.” “Someone should make that happen.”
- Hope\wish. “I hope to get this done by tomorrow.” “I hope we can meet again some day.” “I wish I had time for that.” “I wish this computer was faster.
- Let’s. (not followed by “I . . .”) “Let’s meet sometime.” “Let’s finish this thing.”

**WHAT DOES COMMITMENT SOUND LIKE ?**

- The secret ingredient to recognizing real commitment is to look for sentences that sound like this: I will . . . by . . . (example: I will finish this by Tuesday.)
- You’re stating a **fact** about something YOU will do with a **clear end time**
- You’re not talking about anyone else but yourself.
- You’re talking about an action that you will take
- You won’t “possibly” take it, or “might get to it”; you will achieve it.

**Number of Reasons you might not mean it,**

- It wouldn’t work because I rely on person X to get this done.
  - You can only commit to things that you have full control of
  - If the end goal depends on someone else, you should commit to specific actions that bring you closer to the end goal.
- It wouldn’t work because I don’t really know if it can be done
  - If it can’t be done, you can still commit to actions that will bring you closer to the target.
  - If you can’t make your commitment, the most important thing is to raise a red flag as soon as possible to whoever you committed to
- One important point here is: If you don’t tell anyone about the potential problem as soon as possible, you’re not giving anyone a chance to help you follow through on your commitment.