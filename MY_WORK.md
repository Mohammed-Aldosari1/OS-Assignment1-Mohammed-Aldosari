# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Mohammed Aldosari |
| **Student ID** | 444052541 |
| **University Email** | 444052541@std.psau.edu.sa |
| **GitHub Username** | Mohammed-Aldosari1 |
| **Repository Link** |https://github.com/Mohammed-Aldosari1/OS-Assignment1-Mohammed-Aldosari.git |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 6, 2026, 1:30 PM]

**What I did**: Create a project and repository on GitHub.

**Details**:
-Created a GitHub account using an email from the university
The starting repository was forked. 
-Correctly rename the repository
-I updated SchendulerSimulation.java with my student ID.
-The software ran successfully.

**Challenges**: Initial misunderstanding between a clone and a GitHub fork

**Solution**:
I learned the distinction after seeing a sort tutorial.

**Time spent**: 3 hours

---

### Entry 2 - [October 8, 2026, 6:30 PM]

**What I did**: learned about scheduling logic and studied the starting coed. 

**Details**:
- Analyzed Process class and SchedulerSimulation

-Understood Round-Rodin scheuling

-Observed how threads are created and executed 

-Traced program output step by step

**Challenges**:
Recognizing the relationship between threads and queues

**Solution**:
Go over Coed again and connect it to OS concepts from the textbook.

**Time spent**: 4 hours

---

### Entry 3 - [October 9, 2026, 3 PM]

**What I did**: Implemented Feature 1

**Details**:
-Added priority field (1-5)

-Generated random priority 

-Displayed priority in ready queue

**Challenges**:
 Deciding where to generate priority
**Solution**:
 Added it insidr constructor
**Time spent**:5 hours

---

### Entry 4 - [Date and Time]
**What I did**: Implemented Feature 2

**Details**:
-Added static counter

-lncremented it inside scheduler loop

-Displayed total at end

**Challenges**:
Choosing correct place to increment

**Solution**:
Added after polling thread from queue

**Time spent**: 2 hours

---

### Entry 5 - [October 10, 2026, 12:30 AM]
**What I did**: Implemented Feature 3

**Details**:
-Addes creation time and waiting time

-Calculated waiting time using System.currentTimeMillis()

-Printed summary at end

**Challenges**:
Understanding waiting time calculation

**Solution**:
Simplified formula based on total execution delay

**Time spent**: 2 hour

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: 16 hours

**Most challenging part**: Calculating waiting times and thread behavior

**Most interesting learning**: How Round Robin scheduling guaranties equity

**What I would do differently next time**: Plan features ahead of time and extensively test each component.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:  I discovered that a program can use several threads to carry out tasks thanks to multithreading. I discovered how to define a job using the Runnable interface and start a thread using Thread.start(). I discovered that while Thread, Thread.join() causes one thread to wait for another to finish.The current thread is momentarily paused by sleep() to mimic work. These techniques made it easier for me to comprehend how threads wait and run throughout the Round-Robin scheduling simulation. The fact that a process may require several time slices to complete when its burst time surpasses the time quantum startled me. My comprehension of Java threads and CPU scheduling has improved as a result of this project.** *(5-7 sentences)*

[Write your answer here.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer: Understanding how a process continues to run when its burst time exceeds the time quantum was the most difficult aspect. To find out how much execution time was left, I had to monitor the remainingTime variable. In order to determine whether a process should be rescheduled, I also looked at the ready queue. I was able to make the connection between the code and the scheduling behavior by looking over the program output.
 P3, for instance, had a time quantum of 4000 ms and a burst time of 7630 ms.
  P3 required another execution turn to complete because it had 3630 ms left after its initial execution . ** *(5-7 sentences)*

[Write your answer here.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer: By going over my code and running the program multiple times, I was able to overcome the difficulties. I looked at how processes return to the ready queue and how the `remainingTime` variable functions. In order to comprehend how the time quantum influences execution,
 I also examined the output. For instance, after its initial time slice, P3 has 3630 milliseconds left.
  This improved my comprehension of the scheduling procedure.
 I discovered how to address issues by examining the code and contrasting the outcomes. ** *(5-7 sentences)*

[Write your answer here.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:  I am able to use multithreading in practical applications like media players, games, and web servers.
 Threads are used by web servers to manage numerous user requests. Threads are used in games to handle background processing and visuals.
  Threads are used by media players to play audio while content loads.
   Applications that use multithreading are more responsive and manage tasks more effectively.
  I'll be able to create better Java apps if I understand these ideas. ** *(5-7 sentences)*

[Write your answer here.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer: While threads share memory and resources within the same process, processes are separate programs with their own memory. In general, threads communicate more quickly and have less creation overhead than individual processes. The `Process` class in this assignment depicts a simulated process rather than an actual operating system process. A Java thread is created and executed by the `addProcessToQueue()` method using `new Thread(process)`. We chose to employ threads because they facilitate the Round-Robin algorithm's scheduling and process execution simulation . ** *(3-5 sentences)*

[Write your answer here.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:A process in Round-Robin scheduling goes back to the end of the ready queue for another turn if it doesn't complete within its time quantum. P3 has a time quantum of 4000 ms and a burst time of 7630 ms in the output of my application. After being requeued once, it ran for the final 3630 milliseconds before coming to an end. Other waiting processes can run before P3 has another turn thanks to re-queuing. By distributing CPU time among processes, this encourages equity.** *(3-5 sentences)*

[Write your answer here.]

Example from my output:
```
P3 executing quantum [4000ms]
P3 completed quantum 4000ms
Remaining time: 3630ms
P3 yields CPU for context switch
P3 added to ready queue
P3 executing quantum [3630ms]
P3 completed quantum 3630ms
Remaining time: 0ms
P3 finished execution!

```

**Explanation of example:**
P3 has a time quantum of 4000 ms, yet it needs 7630 ms to execute. P3 gets added to the ready queue once since it has 3630 ms left after its initial turn. Later on, it gets another turn and completes its execution. Re-queuing makes sure that before P3 continues, other ready processes have a chance to utilize the CPU.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*
1. **New:** P1 enters the New state when `new Thread(process)` creates the thread in `addProcessToQueue()`.

2. **Runnable:** P1 becomes Runnable when the scheduler calls `Thread.start()`.

3. **Running:** P1 executes its `run()` method when it gets its turn in the scheduler.

4. **Waiting:** P1 enters Timed Waiting when `Thread.sleep()` pauses it, while the main thread waits for P1 using `Thread.join()`.

5. **Terminated:** P1 reaches this state when its `run()` method finishes and the thread ends.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 CPU Scheduling

**Description**:
Round-Robin scheduling allows an operating system to divide CPU time across several ready jobs. Every assignment is given a set amount of time to complete. A job returns to the ready queue for a subsequent turn if it is not completed. Like the scheduling loop in my simulation, the scheduler alternates between tasks.

**Why Round-Robin works well here**: By allowing each ready task to access the CPU, Round-Robin fosters fairness. By prohibiting a single task from utilizing the CPU continuously for an extended period of time, the time quantum enhances responsiveness. CPU time sharing becomes more predictable as a result.


### Example 2: [Name of application/scenario]

**Description**:
Threads are used by a multithreaded web server to manage requests from several clients. Every worker thread completes duties like preparing a response or processing a request. Before switching to another worker, a Round-Robin-style scheduler can assign a time quantum to each ready worker. This is comparable to how I give each process a turn in my simulation.

**Why Round-Robin works well here**:By providing ready worker threads with opportunities to execute, Round-Robin can advance fairness. When several requests require CPU time, the time quantum might enhance responsiveness. In order to prevent one CPU-intensive job from monopolizing execution, context switching enables the CPU to switch between workers.

## Summary

**Key concepts I understood through these questions:**
1. I recognized the distinction between threads and processes, as well as how Java executes tasks using `Runnable` and `Thread.start()`.
2. I discovered that Round-Robin scheduling distributes CPU time equitably by using a time quantum and ready queue.
3. I was aware of the thread lifecycle and how thread execution is impacted by `Thread.sleep()` and `Thread.join()`.

**Concepts I need to study more:**
1. When several threads access shared data, I need to understand more about thread synchronization and how to avoid race situations.
2. I must comprehend how operating systems handle CPU scheduling in practical applications and context switching.


---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
