# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---

## Example Entry Format:

### Entry 1 - [April 1, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**: 
- Created GitHub account with university email
- Forked the starter repository
- Changed student ID on line 92 to my actual ID (441234567)
- Compiled and ran the program successfully

**Challenges**: Had to install JDK first because javac wasn't recognized

**Solution**: Downloaded JDK 17 from Oracle website and set PATH variable

**Time spent**: 30 minutes

---

## Your Development Log:

### Entry 1 - [ March 28, 2026, 10:30 PM ]
**What I did**: 
Started the assignment and set up GitHub repository

**Details**: 
- Downloaded and installed GitHub
- Created a GitHub account using my university email
-  Forked the assignment repository
- Added my student ID in the code
-  Explored the project files to understand the structure

**Challenges**: 
Was not familiar with GitHub interface and forking process

**Solution**: 
Watched a short tutorial and followed the steps carefully

**Time spent**: 
 45 minutes
---

### Entry 2 - [ March 28, 2026, 11:40 PM ]

**What I did**: 
Ran the project and understood how the scheduler works

**Details**: 
- Compiled the Java code
- Ran the simulation
- Observed how processes move in the ready queue
- Understood Round Robin scheduling logic

**Challenges**: 
Had some confusion understanding how Thread and Process are connected

**Solution**: 
Reviewed the relationship between Thread and Runnable in Java and re-read the code

**Time spent**: 
 2 hours

---

### Entry 3 - [March 29, 2026, 11:00 PM]

**What I did**: 
Implemented Priority feature

**Details**: 
- Added priority field to Process class
- Modified constructor to include priority
- Generated random priority (1–5)
- Displayed priority when adding process to queue
  
**Challenges**: 
Making sure priority is passed correctly between constructor and methods

**Solution**: 
Carefully tracked variables and tested output after each change

**Time spent**: 
2 hours
---

### Entry 4 - [March 30, 2026, 3:00 AM ]

**What I did**: 
Implemented Context Switch counter

**Details**: 
- Added a counter to track the number of context switches
- Incremented it each time a new process starts execution
- Displayed the total number of context switches at the end of the simulation
- Improved the output by printing the ready queue for better visualization


**Challenges**: 
Deciding the correct point in the program to count a context switch

**Solution**: 
Placed the counter update right before the process starts execution to ensure accurate counting

**Time spent**: 
1 hour

---

### Entry 5 - [March 30, 2026, 4:45 AM]

**What I did**: 
Implemented Waiting Time tracking and tested the program

**Details**: 
- Added fields to track waiting time for each process
- Calculated waiting time before each execution
- Stored completed processes in a list
- Displayed a summary table with waiting time
- Ran the simulation multiple times to verify results

**Challenges**: 
Calculating waiting time correctly when processes re-enter the queue

**Solution**: 
Tracked last ready time and used system time difference for accurate calculation

**Time spent**: 
3 hour


---

### Entry 6 - [Optional - Date and Time]
**What I did**: 

**Details**: 

**Challenges**: 

**Solution**: 

**Time spent**: 

---

## Summary

**Total time spent on assignment**: [ 8.5 hours]

**Most challenging part**: 
Implementing the waiting time calculation and making sure it updates correctly as processes move in and out of the ready queue


**Most interesting learning**: 
Understanding how Round Robin scheduling works in practice and how features like priority, context switching, and waiting time can be added to enhance the simulation

**What I would do differently next time**: 
Plan the features more clearly before starting implementation to make the development process smoother

