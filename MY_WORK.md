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
| **Full Name** | [Rena hasan mohammed kariri] |
| **Student ID** | [446052320] |
| **University Email** | [446052320]@std.psau.edu.sa |
| **GitHub Username** | [Rena-446] |
| **Repository Link** | [https://github.com/Rena-446/OS-Assignment1-Rena-Kariri/commits/main/] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/1rZ-I24yjH6_5iePO5XqnLsa0PwD00oPy/view?usp=share_link]

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

### Entry 1 - [September 24, 2026]
**What I did**:
Created a GitHub account using my university email. Forked the starter repository and renamed it for my assignment. Updated the student ID in SchedulerSimulation.java to 446052320. Committed and pushed the changes to GitHub.
**Details**:
Created a GitHub account using My university email.
Forked the starter repository and renamed it for my assignment.
Updated the student ID in SchedulerSimulation.java to 446052320.
Committed and pushed the changes to GitHub.
**Challenges**:
I was new to the repository setup process and needed to understand how to fork and rename the project correctly.
**Solution**:
I followed the repository instructions, configured the project, and verified that my changes appeared on GitHub.
**Time spent**:
40 minutes
---

### Entry 2 - [September 25 , 2026]
**What I did**:
Implemented Feature 1 by adding a priority value to each process in the Round-Robin scheduler simulation.
**Details**:
Added an integer priority value ranging from 1 to 10, where 10 represents the highest priority.
Assigned random priorities to processes.
Updated the ready queue output to display each process’s priority.
Added comments to explain the priority feature.
**Challenges**:
I needed to ensure that process priorities were displayed correctly without changing the original Round-Robin scheduling order.
**Solution**:
I kept priority as a display and tracking feature only, so processes continued to follow the FIFO Round-Robin order.
**Time spent**:
1 hours
---

### Entry 3 - [October 6,2026]
**What I did**:
Implemented Feature 2 by adding a counter to track the total number of context switches during the scheduler simulation.
**Details**:
Added a static integer variable named contextSwitches.
Incremented the counter when a process thread starts.
Displayed the total number of context switches after all processes completed.
Ran the program and verified that the counter appeared in the output.
**Challenges**:
I needed to determine where to increment the counter and how to display the final result after the simulation finished.
**Solution**:
I incremented the counter before currentThread.start() and printed the total after the scheduler simulation completed.
**Time spent**:
2 hours
---

### Entry 4 - [October 6 , 2026]
**What I did**:
Implemented Feature 3 by adding process creation time and total waiting time tracking to the scheduler simulation.
**Details**:
Added creationTime and totalWaitingTime fields to the Process class.
Used System.currentTimeMillis() to record process creation time and calculate waiting time.
Added getters and a setter for the new fields.
Created a summary table showing process names, burst times, and waiting times.
Ran the program to check that the waiting time values appeared in the output.
**Challenges**:
Calculating waiting time correctly and displaying the results in a readable table required careful testing.
**Solution**:
Used the process creation timestamp and burst time in the waiting time calculation, then tested the program to verify that the summary table was displayed.
**Time spent**:
3 hours
---

### Entry 5 - [October 9, 2026]
**What I did**:
Updated Feature 3 to include turnaround time in the final process summary table.
**Details**:
Added a Turnaround Time column to the final summary table.
Calculated turnaround time as the sum of waiting time and burst time.
Updated the table headings to display all four required columns: Process Name, Burst Time, Waiting Time, and Turnaround Time.
Compiled and ran the program from the VS Code terminal to verify that the new column appeared in the output.
**Challenges**:
I needed to update the output table without introducing syntax errors and ensure that the turnaround time calculation followed the assignment requirements.
**Solution**:
Updated the print statements and used totalWaitingTime + burstTime to calculate turnaround time. Then, I compiled and ran the program and confirmed that the four columns appeared in the output.
**Time spent**:
30 minutes
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

**Total time spent on assignment**: [7-8 hours]

**Most challenging part**:
The most challenging part was setting up the Java environment and calculating waiting time correctly. I faced a compilation problem because my initial Java version did not support the String.repeat() method. I solved this by installing JDK 17 and configuring Visual Studio Code to use it. I also needed to make sure the final summary table displayed the required values correctly.
**Most interesting learning**:
The most interesting part was learning how to track process priorities, count context switches, and calculate waiting time and turnaround time. I learned how to use Java variables, methods, and timestamps to add these features to an existing program. Running the simulation helped me understand how the results appear in practice.
**What I would do differently next time**:
Next time, I would review all assignment requirements before starting implementation. I would test each feature separately and commit my changes after completing each part. I would also plan my time earlier to leave enough time for documentation, testing, and the video demonstration.
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

**Your Answer:** *(5-7 sentences)*

[I learned that multithreading allows a program to run multiple threads to perform tasks. In this assignment, I learned how the Thread class is used to create and manage threads. The Thread.start() method starts a new thread and allows it to run independently. I also learned that Thread.sleep() can pause a thread for a short time to simulate work. The Thread.join() method allows one thread to wait for another thread to finish. The most interesting thing I learned was how threads were used in the Round-Robin scheduler simulation to represent processes and display their execution progress.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was setting up the Java environment and understanding the existing code. At first, I had a compilation error because my installed Java version did not support the String.repeat() method. I solved this problem by installing JDK 17 and configuring Visual Studio Code to use it. Another challenge was calculating waiting time and displaying the results correctly. I tested the program after making changes to check that the output was correct. This experience taught me to solve problems step by step instead of changing many things at once.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame the challenges by reading the instructions and examining the existing code carefully. When the Java compilation error appeared, I checked my Java version and installed JDK 17. I then configured Visual Studio Code to use the new version and ran the program again. For each feature, I made small changes and checked the output after testing the code. I also used the terminal to compile and run the program when the Run button did not work. These steps helped me understand the errors and complete the required features more confidently.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading can be useful in many real-world applications. For example, a web browser can use different threads to load web pages, play videos, and respond to user actions. A mobile application can perform background tasks while allowing the user to continue using the interface. In operating systems, multithreading helps different tasks make progress without blocking the entire application. The Round-Robin scheduling concept can help share CPU time fairly among processes that are ready to run. This assignment helped me understand how threads and scheduling concepts can be used to improve responsiveness and manage tasks.]

### Optional: What would you like to learn more about?

[I would like to learn more about how operating systems schedule threads and processes. I am also interested in learning how synchronization prevents multiple threads from accessing shared data incorrectly. I want to understand how multithreading is used in web applications and mobile applications. Learning more about thread safety and performance would help me write better software.]

### Optional: How confident do you feel about multithreading concepts now?

[I feel more confident about the basic concepts of multithreading after completing this assignment. I understand how threads can represent tasks and how scheduling allows processes to make progress. I can also explain the purpose of the priority, context switch counter, waiting time, and turnaround time features I implemented. However, I still need more practice with advanced threading concepts and synchronization. I believe that testing more examples and writing additional programs will improve my understanding.]

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

**Your Answer:** *(3-5 sentences)*

[A process is heavier than a thread because it requires more resources to create and manage. Each process has its own memory space, while threads in the same process share memory and resources. In this assignment, the Process class represents tasks such as P1 and P2, while Java Thread objects execute the simulation work. Threads are more lightweight and usually have less creation and switching overhead than processes.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, a process that does not finish within its time quantum is moved to the end of the ready queue. For example, in my program, P1 runs for its time quantum and is added back to the ready queue because it still has remaining burst time. The program prints a message showing that the process was re-queued, and it can run again after other processes get their turns. This behavior improves fairness because each process gets a chance to use the CPU instead of allowing one process to run until completion.]

Example from my output:
```
[P1 was added back to the ready queue because it still had remaining burst time.]
```

**Explanation of example:**
[This message means that P1 did not finish during its time quantum. The scheduler returned P1 to the end of the ready queue so other processes could run first. P1 will get another turn when the scheduler reaches it again. This allows the CPU to be shared fairly among the processes.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 is in the New state when its Thread object is created but Thread.start() has not been called yet.]

2. **Runnable**: [P1 becomes Runnable when Thread.start() is called, meaning it is ready to run and waiting for CPU time.]

3. **Running**: [P1 is Running when the CPU executes its thread. In the scheduler, P1 gets CPU time to perform its work.]

4. **Waiting**: [P1 enters a waiting state when it waits for another thread to finish, such as when Thread.join() is used.]

5. **Terminated**: [P1 reaches the Terminated state when its run() method finishes executing.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
[An operating system uses Round-Robin scheduling to share CPU time among multiple processes. Each process receives a fixed time quantum to execute its tasks. If a process does not finish, it returns to the ready queue to wait for another turn.]

**Why Round-Robin works well here**:
[Round-Robin improves fairness because every process gets a chance to use the CPU. It also improves responsiveness by preventing one process from using the CPU for too long. The fixed time quantum makes CPU scheduling more predictable.]

### Example 2: [Name of application/scenario]

**Description**:
[A web browser can use multiple threads to load webpages, play videos, and respond to user input. These tasks can run concurrently, helping the browser handle different activities. Threads can share resources within the same application.]

**Why Round-Robin works well here**:
[Round-Robin can help share CPU time fairly among runnable tasks. This helps prevent one task from occupying the CPU for too long. It can improve responsiveness when several tasks need CPU time.]

## Summary

**Key concepts I understood through these questions:**
1.Threads and processes.
2. Round-Robin scheduling and the ready queue.
3.Thread lifecycle and context switching.

**Concepts I need to study more:**
1.Thread lifecycle states.
2.Waiting time and turnaround time.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [x ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ x] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [x ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [x ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ x] Code compiles and runs with no errors
- [ x] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ x] Each feature has clear comments

**Commits**
- [ x] **At least 3 meaningful commits, ideally 6 or more**
- [x ] **One commit per feature**
- [ x] Commits are spread over **different dates** (not all in the last hour)
- [ x] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [x ] Full name and student ID filled in at the top
- [ x] Development log has **5+ entries** on different dates
- [x ] Reflection: 4 questions, 5-7 sentences each
- [x ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ x] No `[...]` placeholders left
- [ x] No section headers deleted

**Video**
- [ x] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [x ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ x] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ x] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
