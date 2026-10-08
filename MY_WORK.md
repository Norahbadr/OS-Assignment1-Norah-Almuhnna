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
| **Full Name** | [Norah badr Almuhnna ] |
| **Student ID** | [446051848 ] |
| **University Email** | [ 446051848@std.psau.edu.sa ] |
| **GitHub Username** | [Norahbadr]|
| **Repository Link** | [https://github.com/Norahbadr/OS-Assignment1-Norah-Almuhnna] |
 
---

## 🎥 Video Link

**Video Link**: (https://drive.google.com/drive/folders/1ThOfVJb5Dg8vGvYBbT8xZCf9fhAtaeBZ)

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

### Entry 1 - [October 05, 2026, 4:15 PM]
**What I did**: Set up repository environment, configured Git, and set Student ID.

**Details**: - Forked and cloned the repository in VS Code.
- Configured Git `user.name` and `user.email` in the integrated terminal to fix the configuration pop-up.
- Modified line 150 in `SchedulerSimulation.java` to set my actual student ID (`446051848`).
- Verified compilation and committed initial changes.

**Challenges**: Git popped up a configuration warning blocking the first commit because user credentials were not set.

**Solution**:`git config user.email "446051848@std.psau.edu.sa"` and `git config user.name "Norahbadr"` in the terminal.

**Time spent**: 4 hours

---

### Entry 2 - [October 06, 2026, 2:00 PM]
**What I did**: Implemented Feature 1 (Process Priority Attribute and Display).

**Details**: - Added an integer field `priority` to the `Process` class.
- Updated constructor to initialize random priority (1–10) using `Random(studentID)`.
- Added priority getters and updated `run()` and `addProcessToQueue()` console outputs to show priority.
- Committed changes: `Feature 1: Introduced process priority attribute and display`.

**Challenges**: Formatting the ANSI colored output to cleanly present priority without breaking log alignment.

**Solution**: Adjusted output strings using colored brackets `(Priority: X)` right after process names.

**Time spent**: 6 hours

---

### Entry 3 - [October 06, 2026, 8:00 PM]
**What I did**: Implemented Feature 2 (Context Switch Counter).

**Details**: - Declared `private static int totalContextSwitches = 0;` in `SchedulerSimulation`.
- Incremented `totalContextSwitches++` inside the main scheduling loop whenever a process thread is polled.
- Displayed `Total Context Switches` at the end of the simulation.
- Committed changes: `Feature 2: Implemented context switch tracking mechanism`.

**Challenges**: Distinguishing between process creation enqueues and actual CPU context switches.

**Solution**: Placed the counter increment strictly inside the active queue execution loop right before `currentThread.start()`.

**Time spent**: 4 hours

---

### Entry 4 - [October 07, 2026, 12:00 AM]
**What I did**: Implemented Feature 3 (Waiting Time, Turnaround Time, and Summary Table). 

**Details**: - Added `finishTime`, `waitingTime`, and `turnaroundTime` variables to `Process`.
- Created simulation clock `currentTime` to track time passage during quantum execution and completion.
- Formatted and printed an ASCII table showing process metrics and overall average waiting/turnaround times.
- Committed changes: `Feature 3: Added waiting time calculation and reporting`.

**Challenges**: Accurately tracking `currentTime` when a single remaining process skips quantum slicing using `runToCompletion()`.

**Solution**: Added remaining burst time to `currentTime` inside the `runToCompletion()` execution block before recording finish time.

**Time spent**: 4 hours

---

### Entry 5 - [October 08, 2026, 2:00 PM]
**What I did**: Completed technical answers, documentation, and final testing.

**Details**: - Ran full test simulation to verify output correctness and table accuracy with Student ID `446051848`.
- Completed all technical, reflection, and theoretical questions in `MY_WORK.md`.
- Prepared commit history and workspace for demo video recording.

**Challenges**: Explaining thread lifecycle transitions accurately in technical answers based on exact line calls.

**Solution**: Traced method invocations (`Thread.start()`, `Thread.sleep()`, `currentThread.join()`) line-by-line in source code.

**Time spent**: 7 hours

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

**Total time spent on assignment**: [25 hours]

**Most challenging part**: Managing exact time tracking for Feature 3 across quantum yields and process completion states.

**Most interesting learning**: Understanding how thread synchronization via `join()` coordinates simulated CPU Round-Robin scheduling.

**What I would do differently next time**: Push small modular commits more frequently immediately after testing each method.

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

[This assignment taught me how Java manages threads and how they operate in the background. I realized that the Process class makes use of Runnable, and that while Thread.sleep() simulates CPU execution time, calling Thread.start() executes tasks in parallel. A crucial idea was to utilize Thread.join(), which forces the scheduler to wait until the process has completed its quantum before continuing. I was quite aback by how quickly context switching occurs and how crucial thread state control is. I now have a better understanding of how real operating systems distribute CPU time across various tasks. All things considered, writing this code helped me better understand and comprehend theoretical OS ideas.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[Working on Feature 3 and precisely measuring the current time was the most challenging aspect for me. Calculating the waiting and turnaround times for each step was challenging, particularly when alternating between quantum yields and completed operations. It was difficult for me to handle runToCompletion() for the final process so that the clock was accurately updated with its remaining burst duration. It also required some extra work to arrange the ASCII summary table with various number lengths such that it appeared tidy and well-organized. To address these timing issues, I spent a great deal of effort testing and debugging SchedulerSimulation.java's scheduling loop. Careful, step-by-step verification was necessary to get the figures to match.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[By taking my time and gradually testing my code, I was able to overcome these issues. To see what was going on during execution, I added several System.out.println() commands inside the loop to print currentTime and remaining burst times. I re-read the README.md instructions and examined Thread.join() to ensure that my time calculations took place at the appropriate time. Every time I modified a line of code, I compiled and ran the program with my student ID 446051848 to confirm the results. Working on small parts one by one allowed me to fix Feature 3 without breaking the earlier features. Keeping a development log also helped me stay organized throughout the assignment.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Software uses multithreading everywhere to maintain responsiveness and speed. Web browsers, for instance, employ separate threads to prevent the page you are viewing from freezing while downloading a file or executing JavaScript. Background threads are also used by media players and video games to process visuals or stream audio while still reacting to keyboard and mouse inputs. To manage numerous users browsing a website simultaneously without delay, web servers use threads. Threads are even used by mobile apps to load data from the internet while maintaining fluid screen animations. Developers may create programs that operate effectively on multi-core systems by having a solid understanding of threads.]

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

**Your Answer:** *(3-5 sentences)*

[A process is an independent program running in its own memory space, while a thread is a smaller, lightweight unit of execution that runs inside a process and shares its memory. In this assignment, we used Java threads instead of separate processes because threads are much faster to create, consume less system memory, and can share data easily without needing complex inter-process communication. In our code, the class named `Process` is actually just a custom object simulating a task, which is then executed by a real Java thread using `new Thread(process)` in `addProcessToQueue()`. Using threads allowed us to simulate a working CPU scheduler smoothly inside a single Java application..]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, if a process cannot finish its total execution within the 5000ms time quantum, the scheduler preempts it and puts it back at the end of the ready queue. This prevents long processes from holding the CPU for too long and gives every process a fair chance to execute. In my output with Student ID 446051848, process P6 had a large burst time of 11980ms, so it had to be re-queued twice after its first execution turn. Re-queueing keeps the system fair and ensures shorter tasks can finish without waiting too long.]

Example from my output:
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```
⚙ P6 (Priority: 8) executing quantum [5000ms]
✔ Quantum progress: [███████████████] 100%
⚙ P6 completed quantum 5000ms │ Overall progress: [████████░░░░░░░░░░░░] 41%
Remaining time: 6980ms
↻ P6 yields CPU for context switch
⚙ P6 (Priority: 8) added to ready queue │ Burst time: 11980ms
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P8 ➔ P9 ➔ P10 ➔ P11 ➔ P12 ➔ P13 ➔ P14 ➔ P15 ➔ P16 ➔ P17 ➔ P18 ➔ P1 ➔ P2 ➔ P3 ➔ P5 ➔ P6]
└───────────────────────────────────────────────────────────────────────────────
**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]
In this log snippet, P6 started with a burst time of 11980ms, which is larger than the 5000ms quantum. The scheduler executed P6 for 5000ms, leaving 6980ms remaining, and then paused it. P6 yielded the CPU and was placed at the end of the ready queue behind P5 so other processes could run before P6 gets another turn.
## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*
A thread transitions through different states during execution as managed by the scheduler in our program.

1. **New**: [When is P1 in the New state?] : P1 enters the New state right after `Thread pThread = new Thread(process)` is instantiated inside the `addProcessToQueue()` method.

2. **Runnable**: [When does P1 become Runnable?] : P1 moves to the Runnable state when the scheduler calls `pThread.start()`, making it ready for the Java thread scheduler to pick up.

3. **Running**: [When is P1 Running?] : P1 enters the Running state when it is assigned CPU execution time and its `run()` method starts executing its quantum loop.

4. **Waiting**: [When and why would a thread be Waiting?] : The main thread enters the Waiting state when it calls `pThread.join()` to wait for P1 to finish its quantum; meanwhile, P1's thread temporarily pauses using `Thread.sleep()`.

5. **Terminated**: [When is P1 Terminated?] : P1 reaches the Terminated state when its `run()` method completes execution and the thread completely finishes.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling in Desktop Operating Systems]

**Description**:
[An operating system kernel uses Round-Robin scheduling to distribute CPU time among active applications, like a code editor, a music player, and a web browser. Each application receives a small time slice before the OS context switches to the next program.]

**Why Round-Robin works well here**:
[It provides high responsiveness and fairness because no single application can freeze the system or hog the CPU, keeping the user interface smooth and interactive.]

### Example 2: [Web Server Request Handling]

**Description**:
[Web servers handling thousands of concurrent user visits use thread pools with time-slicing to process incoming HTTP requests. Each thread works on a user request for a brief time slice before giving turn to other incoming requests.]

**Why Round-Robin works well here**:
[It maintains predictable response times and prevents heavy tasks, like fetching large database records, from delaying quick page requests for other online users.]

## Summary

**Key concepts I understood through these questions:**
1. How Java threads represent and run simulated tasks.
2. How Round-Robin maintains scheduling fairness through preemptive re-queueing.
3. How thread lifecycle states transition using start(), sleep(), and join().

**Concepts I need to study more:**
1. Synchronization tools like semaphores and mutexes.
2. Advanced OS scheduling algorithms like Multi-Level Feedback Queues.

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
