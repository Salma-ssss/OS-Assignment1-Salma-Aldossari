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
**What I did**: Set up GitHub repository and project
**Details**: 
-Created a GitHub account using university email
-Forked the starter repository
-Renamed the repository correctly
-Added my student ID in SchedulerSimulation.java
-Ran the program successfully

**Challenges**: Initial confusion with GitHub fork vs clone

**Solution**: Watched a short tutorial and understood the difference

**Time spent**: 5 hours

---

## Your Development Log:

### Entry 1 - []
**What I did**: 

**Details**: 

**Challenges**: 

**Solution**: 

**Time spent**: 

---

### Entry 2 - [April 1 , 2026, 5:30 PM]
**What I did**: Studied the starter code and understood scheduling logic

**Details**: 
-Analyzed Process class and SchedulerSimulation
-Understood Round-Robin scheduling
-Observed how threads are created and executed
-Traced program output step by step

**Challenges**: Understanding how threads interact with the queue

**Solution**: Re-read the code and linked it with OS concepts from the textbook

**Time spent**: 2 huors

---

### Entry 3 - [April 1 , 2026, 8:30 PM]
**What I did**: Implemented Feature 1 (Process Priority)

**Details**: 
-Added priority field (1-5)
-Generated random priority
-Displayed priority in ready queue

**Challenges**: Deciding where to generate priority

**Solution**: Added it inside constructor

**Time spent**: 1 hours

---

### Entry 4 - [April 1 , 2026, 9:30 PM]
**What I did**: Implemented Feature 2 (Context Switch Counter)

**Details**: 
-Added static counter
-Incremented it inside scheduler loop
-Displayed total at end

**Challenges**: Choosing correct place to increment

**Solution**: Added after polling thread from queue

**Time spent**: 50 minutes

---

### Entry 5 - [April 1 , 2026, 10:20 PM]
**What I did**: Implemented Feature 3 (Waiting Time)

**Details**: 
-Added creation time and waiting time
-Calculated waiting time using System.currentTimeMillis0
-Printed summary at end
**Challenges**: Understanding waiting time calculation

**Solution**: Simplified formula based on total execution delay

**Time spent**: 40 minutes

---

### Entry 6 - [Optional - Date and Time]
**What I did**: 

**Details**: 

**Challenges**: 

**Solution**: 

**Time spent**: 

---

## Summary

**Total time spent on assignment**: [2 days]

**Most challenging part**: Waiting time calculation and thread behavior

**Most interesting learning**: How Round-Robin scheduling ensures fairness

**What I would do differently next time**: Plan features earlier and test each part more thoroughly
