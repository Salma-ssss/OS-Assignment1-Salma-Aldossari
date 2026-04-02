# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:A process is an independent program in execution with its own memory space, while a thread is a smaller unit of execution within a process that shares the same memory. Processes are heavier and require more resources to create and manage, while threads are lightweight and faster to create. Threads share memory, which makes communication easier and faster compared to processes. In this assignment, threads were used because they allow efficient simulation of multiple processes within the same program. Using separate processes would require more overhead and complex communication mechanisms.**

[Write your answer here. Consider: What is a process? What is a thread? How do they differ in terms of memory, resources, creation overhead? Why are threads more suitable for this simulation?]

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:In Round-Robin scheduling, if a process does not finish within its time quantum, it is moved back to the ready queue to wait for another turn. This ensures that all processes get fair access to the CPU and no process monopolizes execution.**

[Write your answer here. Describe the specific behavior - where does the process go? When does it run again? Give an example from your actual program output showing a process that was re-queued.]

Example from my output:

P1 completed quantum 4000ms | Overall progress: 51%
Remaining time: 3837ms
P1 yields CPU for context switch

P1 added to ready queue |Burst time: 7837ms |Priority: 4

Explanation of example:
In this example, process P1 executed for its full time quantum (4000ms) but did not complete because it still had 3837ms remaining. As a result, it yielded the CPU and was placed back into the ready queue. This behavior allows other processes (such as P2, P3, etc.) to execute before P1 gets another turn. This mechanism ensures fairness and prevents starvation in the system


## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**
1. New.
P1 is in the New state when the thread is created using:
Thread thread new Thread(process);
At this stage, the thread has been created but has not started execution yet.
2. Runnable:
P1 enters the Runnable state when start() is called:
currentThread.start();
At this point, the thread is ready to run and waiting for CPU scheduling.
3. Running
P1 is in the Running state when the CPU executes its run() method. This is shown in the output:
P1 executing quantum [4000ms]
Quantum progress: -100%
Here, the thread is actively using the CPU.
4. Waiting:
P1 enters the Waiting state when Thread.sleep() is called inside the run method during execution. This simulates the execution delay of the process while it is temporarily inactive.
5. Terminated:
P1 reaches the Terminated state when its execution finishes completely, as shown in the output.
P1 completed quantum 1837es. Overall progress: 100%
Resaining time: ens
Pi finished execution!

At this point, the thread has completed its task and will not run again.

---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: Web Server

**Description**: A web server handles multiple client requests simultaneously using threads


**Why Round-Robin works well here**: Round-Robin ensures fairness by giving each request a small time slice. This improves responsiveness and prevents any single request from blocking others

### Example 2: Operating System Task Scheduling

**Description**: An operating system schedules multiple running applications using CPU scheduling algorithms

**Why Round-Robin works well here**: It ensures that all processes get CPU time in a fair manner. It also improves system responsiveness, especially for interactive applications.
---

## Summary

**Key concepts I understood through these questions:**
1. Difference between threads and processes
2. Round-Robin scheduling behavior
3. Thread lifecycle 

**Concepts I need to study more:**
1. Thread synchronization
2. Advanced scheduling algorithms 
