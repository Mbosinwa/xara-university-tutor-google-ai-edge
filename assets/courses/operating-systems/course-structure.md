---
courseName: Operating Systems
courseCode: CMS701
subjectDomain: Computer Science
lecturer: Dr. I.B. Cookey
materialsCount: 4
status: Active
created: 2026-04-02
lastUpdated: 2026-04-02
---

# Course Structure: Operating Systems (CMS701)

## Materials Index

| # | Filename | Title | Type | Status |
|---|----------|-------|------|--------|
| 1 | 01-course-outline.md | Course Outline — Operating Systems | Direct text | ✓ Processed |
| 2 | 02-lecture-notes-os-types-kernels-system-calls.md | Lecture Notes — OS Types, Kernels & System Calls (Dr. I.B. Cookey) | Direct text | ✓ Processed |
| 3 | 03-lecture-notes-process-state-pcb-schedulers.md | Lecture Notes — Process State, PCB & Schedulers (Dr. I.B. Cookey) | Direct text | ✓ Processed |
| 4 | 04-lecture-notes-multithreading-cpu-scheduling-synchronization.md | Lecture Notes — Multithreading, CPU Scheduling & Synchronization (Dr. I.B. Cookey) | Direct text | ✓ Processed |

---

## Topics

### Primary Topics

1. **Introduction to Operating Systems**
   - Definition and role of an OS
   - OS as bridge between user and hardware
   - Types of OS: Batch, Multiprogramming, Time Sharing, Network, Real-Time

2. **OS Structures** *(Course Outline Topic)*
   - Kernel Architecture (Monolithic, Microkernel, Hybrid, Exokernel, Nanokernel)
   - System Calls — types and mechanics
   - System Programs
   - Spooling *(outline topic — not yet in lecture notes)*
   - Mechanisms and Policies *(outline topic — not yet in lecture notes)*

3. **Process Management** *(Course Outline Topic)*
   - Definition of a Process
   - Process Attributes and Components
   - Process Creation (Parent/Child, Resource Allocation, Execution Models)
   - Context Switching
   - Process State Models (Two-State, Five-State, Seven-State)
   - Process Control Block (PCB) — anatomy and fields
   - Process Schedulers (Long-Term, Short-Term, Medium-Term)

4. **CPU Scheduling**
   - Preemptive vs. Non-Preemptive Scheduling
   - Scheduling Terminologies (Arrival Time, Burst Time, Turnaround Time, Waiting Time)
   - Scheduling Algorithms: FCFS, SJF, Priority, Round Robin, Multilevel Queue, Multilevel Feedback Queue

5. **Thread Management**
   - Definition of a Thread (Lightweight Process)
   - Thread Characteristics and Components (Stack, Registers, Program Counter)
   - Types of Threads: User-Level vs. Kernel-Level
   - Advantages of Threads

6. **Multithreading**
   - What is Multithreading
   - Multithreading Models: Many-to-Many, Many-to-One, One-to-One
   - Multithreading vs. Multitasking vs. Multiprocessing
   - Common Issues: Race Conditions, Deadlocks, Starvation

7. **Process Synchronization**
   - Race Conditions
   - Critical Section Problem
   - Synchronization Requirements: Mutual Exclusion, Progress, Bounded Waiting
   - Synchronization Mechanisms: Mutexes, Semaphores, Monitors, Condition Variables
   - Synchronization Problems: Deadlock, Starvation, Data Inconsistency

---

## Key Concepts

| Concept | Brief Description | Source Material |
|---------|-------------------|-----------------|
| Operating System | Software bridge between user and hardware; manages all resources | 02-lecture-notes |
| Kernel | Core of the OS; manages CPU, memory, devices | 02-lecture-notes |
| System Call | Request from user-mode program to kernel for privileged operations | 02-lecture-notes |
| Process | A program in execution with its own code, state, and resources | 02-lecture-notes |
| Thread | Smallest unit of execution within a process; lightweight process | 02, 04-lecture-notes |
| Process Control Block (PCB) | OS data structure storing all info needed to manage a process | 03-lecture-notes |
| Context Switch | OS saving state of one process and loading another to share CPU | 02-lecture-notes |
| CPU Scheduling | OS decision-making on which process/thread runs on CPU next | 03, 04-lecture-notes |
| Preemptive Scheduling | OS can interrupt a running process for a higher-priority one | 03, 04-lecture-notes |
| Non-Preemptive Scheduling | Process holds CPU until finished or voluntarily waiting for I/O | 03, 04-lecture-notes |
| Race Condition | Two+ processes access shared data simultaneously → unpredictable results | 04-lecture-notes |
| Critical Section | Code segment accessing shared resources; only one process at a time | 04-lecture-notes |
| Mutual Exclusion | Only one process may be in the critical section at any time | 04-lecture-notes |
| Deadlock | Two+ processes stuck in circular wait for each other's resources | 04-lecture-notes |
| Starvation | A process perpetually denied CPU/resource due to priority | 04-lecture-notes |
| Semaphore | Synchronization object using a count to control resource access | 04-lecture-notes |
| Multithreading | Single process running multiple concurrent threads | 04-lecture-notes |
| Time Quantum | Small CPU time slice allocated per process in Round Robin scheduling | 03, 04-lecture-notes |
| Program Counter (PC) | Holds address of next instruction to execute in a process/thread | 02, 03-lecture-notes |
| Dispatcher | Component that performs the actual CPU context switch | 03-lecture-notes |
| Zombie Process | Finished process whose PCB remains because parent hasn't read its exit status | 03-lecture-notes |
| Aging | Gradually increasing priority of long-waiting processes to prevent starvation | 04-lecture-notes |
| Convoy Effect | FCFS problem: short jobs stuck behind a long job | 04-lecture-notes |
| IPC | Mechanism for processes/threads to communicate and share data | 02-lecture-notes |

---

## Definitions

### Operating System
The main software that makes the computer or mobile device work. It acts as a bridge between the user and the computer hardware. Examples: Windows, Linux, Unix, macOS, Android.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Kernel
The core part of an Operating System. Acts as a bridge between software applications and the hardware of a computer. Manages system resources — CPU, memory, and devices.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Monolithic Kernel
A single large program containing all OS core functions including device drivers, file system management, and system calls. High performance but crash-vulnerable.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Microkernel
Keeps only the absolute essentials in kernel space (basic process scheduling, IPC). Everything else — drivers, file systems — runs in User Space. More stable and modular; slower due to IPC overhead.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Hybrid Kernel
Combines monolithic and microkernel approaches — modular like a microkernel, but runs most services in kernel space for monolithic-level speed. Examples: Windows NT, macOS XNU.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Exokernel
Gives applications direct hardware access, letting them manage resources themselves. Maximum efficiency for specialized apps; applications must be more complex.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Nanokernel
An extreme microkernel — handles only hardware interrupts. Tiny memory footprint; used in embedded/IoT systems.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### System Call
A request made by a program to the kernel to perform a task the program cannot perform directly. The bridge between user mode and kernel mode.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Process
A program in execution, including the program code, current activity, and state information.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Thread
The smallest unit of execution within a process. A lightweight process with its own program counter, registers, and stack. Shares memory and resources with other threads in the same process.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Process Control Block (PCB)
A data structure maintained by the OS containing all information needed to manage a process: PID, state, program counter, CPU registers, memory info, scheduling info, and I/O info. The OS's "identity card" for each process.
*Source: 03-lecture-notes-process-state-pcb-schedulers.md*

### Context Switch
The process by which the OS saves the state of a running process and loads the state of another, enabling multiple processes to share the CPU effectively.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Critical Section
A segment of code where a process accesses shared resources. Only one process should execute in the critical section at a time to prevent race conditions.
*Source: 04-lecture-notes-multithreading-cpu-scheduling-synchronization.md*

### Semaphore
A synchronization object that maintains a count and allows or restricts resource access. Binary semaphore (0 or 1) acts as a lock; counting semaphore allows multiple concurrent accesses up to a limit.
*Source: 04-lecture-notes-multithreading-cpu-scheduling-synchronization.md*

### Deadlock
A situation where two or more processes are stuck in a circular wait — each holding a resource the other needs, and neither can proceed.
*Source: 04-lecture-notes-multithreading-cpu-scheduling-synchronization.md*

### Turnaround Time
Time difference between process completion and arrival: `Turnaround Time = Completion Time − Arrival Time`
*Source: 04-lecture-notes-multithreading-cpu-scheduling-synchronization.md*

### Waiting Time
Time a process spends waiting in the ready queue: `Waiting Time = Turnaround Time − Burst Time`
*Source: 04-lecture-notes-multithreading-cpu-scheduling-synchronization.md*

### Spooling
*(Defined in course outline; lecture notes pending)* — A technique where data is temporarily held in a buffer (typically on disk) to be used and executed by a device, program, or system. Common example: print spooling.

### Multithreading
A technique where a process is divided into smaller execution units (threads) that run concurrently, allowing different parts of a program to run simultaneously.
*Source: 04-lecture-notes-multithreading-cpu-scheduling-synchronization.md*

---

## Examples

### OS Types — Bank Teller (System Call Analogy)
You (application) cannot walk behind the bank counter (kernel mode) to grab cash (hardware access) yourself. You fill a withdrawal slip (system call), hand it to the teller (kernel), who validates and executes it, then returns the result to you.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Kernel Types — Monolithic (Startup Analogy)
Everyone in one big room — fast communication (high performance), but one sick employee (buggy driver) can infect the whole office (crash the OS).
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Kernel Types — Microkernel (Government Agency Analogy)
Each department in a separate building — one department burns down (driver crashes), the rest of the government keeps running. But formal letters (IPC) are slower than shouting across a room.
*Source: 02-lecture-notes-os-types-kernels-system-calls.md*

### Context Switch — Student Multitasking
A student runs C++ program, listens to music, downloads lecture slides, and runs antivirus. The scheduler assigns CPU to each in rapid succession (milliseconds), giving the illusion of simultaneous execution.
*Source: 03-lecture-notes-process-state-pcb-schedulers.md*

### PCB — Zombie Process
A child process finishes, but its PCB remains because the parent hasn't read its exit status. Consumes no CPU but occupies a slot in the OS process table.
*Source: 03-lecture-notes-process-state-pcb-schedulers.md*

### Race Condition — Bank Account
Balance ₦10,000. Process A withdraws ₦7,000; Process B withdraws ₦5,000. Without sync: both read ₦10,000, both succeed → incorrect balance. With sync: A goes first → balance ₦3,000 → B denied (insufficient funds).
*Source: 04-lecture-notes-multithreading-cpu-scheduling-synchronization.md*

### Deadlock — Circular Wait
Process A holds Resource 1 and waits for Resource 2. Process B holds Resource 2 and waits for Resource 1. Both stuck forever.
*Source: 04-lecture-notes-multithreading-cpu-scheduling-synchronization.md*

### Round Robin — Shared Computer
Students take turns on a shared computer — 5 minutes each. If not done, move to back of queue. Fair but frequent context switches.
*Source: 04-lecture-notes-multithreading-cpu-scheduling-synchronization.md*

### Multithreading — Banking System
Many users perform transfers, deposits, payments simultaneously on bank servers. Each activity is a separate thread — no user waits for another to finish.
*Source: 04-lecture-notes-multithreading-cpu-scheduling-synchronization.md*

### Many-to-Many Model — Large Server
100 user threads handle requests; OS maps them to 10 kernel threads. Some run in parallel, others wait without blocking the entire system.
*Source: 04-lecture-notes-multithreading-cpu-scheduling-synchronization.md*

---

## Relationships

| From | Relationship | To |
|------|-------------|-----|
| Operating System | contains as core component | Kernel |
| Kernel | bridges | Software Applications ↔ Hardware |
| User Mode | requires system call to access | Kernel Mode |
| System Call | transfers control to | Kernel |
| Process | is managed via | Process Control Block (PCB) |
| Process | transitions through | Process States (New → Ready → Running → Blocked → Terminated) |
| Context Switch | is triggered by | Time Quantum Expiration / Interrupt / Mode Switch |
| Context Switch | saves and restores | PCB (CPU Registers, Program Counter) |
| Thread | is lightweight version of | Process |
| Thread | shares memory space with | Sibling Threads (same process) |
| Multithreading | is an extension of | Multitasking |
| Many-to-One Model | maps | Multiple User Threads → One Kernel Thread |
| One-to-One Model | maps | Each User Thread → Dedicated Kernel Thread |
| Many-to-Many Model | multiplexes | Many User Threads → Equal or Fewer Kernel Threads |
| Race Condition | requires solution via | Process Synchronization |
| Critical Section | protected by | Mutual Exclusion |
| Mutual Exclusion | implemented with | Semaphores / Mutexes / Monitors |
| Starvation | prevented by | Aging (in Priority Scheduling) |
| Deadlock | caused by | Circular Resource Wait |
| FCFS | suffers from | Convoy Effect |
| SJF | risks causing | Starvation (long jobs never run) |
| Round Robin | performance depends on | Time Quantum size |
| Priority Scheduling | prevents starvation via | Aging |
| Long-Term Scheduler | controls | Degree of Multiprogramming |
| Short-Term Scheduler | selects from | Ready Queue |
| Medium-Term Scheduler | performs | Swapping (Main Memory ↔ Secondary Storage) |
| Monolithic Kernel | trades stability for | Performance |
| Microkernel | trades performance for | Stability and Modularity |
| Hybrid Kernel | balances | Monolithic Performance + Microkernel Modularity |
