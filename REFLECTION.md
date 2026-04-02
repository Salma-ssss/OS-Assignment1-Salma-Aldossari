# Reflection Questions

## Instructions
Answer the following questions about your learning experience. Each answer should be **at least 5-7 sentences** and show your understanding.

---

## Question 1: What did you learn about multithreading?

**Your Answer: This project taught me how Java's Runnable interface is used to create and manage threads. I understood how, despite sharing a CPU, many threads might mimic concurrent operation. Additionally, I gained knowledge of thread lifecycle states as New, Runnable, Running, and Terminated. One key idea that I grasped is how Thread.join() guarantees synchronization and Thread.start() starts execution. I also became aware of the equitable distribution of CPU time among threads by scheduling methods such as Round-Robin. I was able to make the connection between textbook theory and practical application thanks to this project.**

[Write your answer here. Discuss specific concepts like thread creation, thread states, how threads execute concurrently, what surprised you, etc.]

---

## Question 2: What was the most challenging part of this assignment?

**Your Answer:The hardest aspect was figuring out how the scheduler works with the queue and threads. The mechanism of re-adding processes to the queue after partial execution was initially unclear. Correctly implementing the waiting time feature presented another difficulty since it required an understanding of how time is tracked in actual systems. It was also challenging to decide where to make code changes without altering the original reasoning. The situation becomes more complicated due to the interplay between threads and time. In general, it required both conceptual knowledge and code.**

[Describe the specific challenge. Was it understanding the code? Implementing a feature? Using Git? Explain what made it difficult and how it relates to the course concepts.]

---

## Question 3: How did you overcome the challenges you faced?

**Your Answer:I overcame these challenges by carefully reading the code multiple times and relating it to concepts from the Operating Systems textbook. I also tested the program frequently after each modification to ensure correctness. Breaking the problem into smaller steps helped me focus on one feature at a time. Additionally, I used debugging techniques like printing intermediate values ​​to understand program behavior. Watching tutorials about multithreading also helped reinforce my understanding. Gradually, I became more confident in modifying the code.**

[Describe your problem-solving approach. Did you read documentation? Ask for help? Debug systematically? What resources did you use? What strategies worked?]

---

## Question 4: How can you apply multithreading concepts in real-world applications?

**Your Answer:Multithreading is widely used in real-world applications such as web browsers, where each tab runs as a separate thread. It is also used in servers to handle multiple client requests simultaneously. In gaming, threads are used to manage rendering, physics, and user input concurrently. Media players use threads to play audio/video while handling user controls. This assignment helped me understand how threads improve responsiveness and efficiency. It also showed how scheduling ensures fair resource allocation.**

[Give specific examples from real applications you use (web browsers, games, mobile apps, etc.). Explain why threads are useful in those scenarios. Connect to what you learned in this assignment.]

---

## Additional Reflections (Optional)

### What would you like to learn more about?
would like to learn more about advanced scheduling algorithms such as priority scheduling and multi-level feedback queues. I am also interested in synchronization techniques like semaphores and mutexes. Understanding deadlocks and how to prevent them is another area I want to explore. Additionally, I want to study how operating systems manage threads at the kernel level. These topics would deepen my understanding of concurrency.

[Any topics related to threading, concurrency, or operating systems that you're curious about?]

---

### How confident do you feel about multithreading concepts now?
would rate myself as Intermediate. I understand the basic concepts such as thread creation, lifecycle, and scheduling. I can also implement simple multithreading programs like this assignment. However, I still need more practice with complex synchronization problems and real-world systems. Overall, my confidence has improved significantly after completing this assignment

[Rate yourself and explain: Beginner / Intermediate / Confident]

[Explain your rating - what do you understand well? What needs more practice?]

---

### Feedback on the assignment

[Any comments about the assignment? Was it helpful? Too easy/hard? Suggestions for improvement?]
