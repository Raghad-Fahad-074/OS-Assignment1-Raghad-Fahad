# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:**

[  A process is an independent program that has its own memory space and system resources, while a thread is a smaller unit of execution within a process. Threads share the same memory space, whereas processes do not share memory and require inter-process communication to exchange data. In this assignment, threads were used instead of separate processes because threads are lighter in weight and have lower creation overhead. Communication between threads is also faster since they share the same memory, unlike processes which require more complex communication methods. Using threads was more suitable for this simulation because it represents how CPU scheduling works within a single system efficiently. In SchedulerSimulation.java, each process is executed using threads to simulate concurrent execution.]

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:**

[  In Round-Robin scheduling, if a process does not finish within its assigned time quantum, it is moved back to the end of the ready queue. This ensures that all processes get a fair share of CPU time. The process will then wait for its next turn in the queue and will be executed again when it reaches the front. ]

Example from my output:
```
[  P1 executing quantum [4000ms] ? Quantum progress: [???????????????] 100% ? P1 completed quantum 4000ms ? Overall progress: [????????????????????] 44% Remaining time: 4977ms ? P1 yields CPU for context switch ? P1 (Priority: 2) added to ready queue ? Burst time: 8977ms ?? Ready Queue ????????????????????????????????????????????????????????????????? ? [P3 ? P4 ? P5 ? P6 ? P7 ? P8 ? P9 ? P10 ? P11 ? P12 ? P13 ? P14 ? P1] ???????????????????????????????????????????????????????????????????????????????? ]
```

**Explanation of example:**
[  a process such as P1 ,  executes for its time slice and then yields the CPU. If it still has remaining burst time, it is re-added to the ready queue and waits for other processes to execute first before it gets another turn ]

---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**

[Write your answer here. For each state, explain when P1 enters that state during the simulation. Use your understanding of the code to trace through the lifecycle.]

1. **New**: [When is P1 in New state?]

2. **Runnable**: [When does P1 become Runnable?]

3. **Running**: [When is P1 Running?]

4. **Waiting**: [When/why would P1 be Waiting?]

5. **Terminated**: [When is P1 Terminated?]

---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: [Name of application/scenario]

**Description**: 
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

### Example 2: [Name of application/scenario]

**Description**: 
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

---

## Summary

**Key concepts I understood through these questions:**
1. 
2. 
3. 

**Concepts I need to study more:**
1. 
2. 
