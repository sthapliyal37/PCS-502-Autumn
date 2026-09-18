# Operating Systems Laboratory

**Graphic Era Deemed to be University**  
**Department of Computer Science and Engineering**  
**Academic Session:** 2026–27

This repository contains the programs and practical exercises for the **Operating Systems Laboratory**. The lab focuses on Unix/Linux system programming using the C programming language and provides hands-on implementation of process management, inter-process communication, CPU scheduling, and memory management concepts.

---

## 🎯 Lab Objectives

The laboratory is designed to help students:

- Understand process creation and management using `fork()`.
- Study parent and child process relationships using `getpid()` and `getppid()`.
- Implement process synchronization using `wait()` and related system calls.
- Understand orphan and zombie processes.
- Implement Inter-Process Communication (IPC) mechanisms.
- Use the `exec()` family of system calls.
- Implement CPU scheduling algorithms.
- Implement page replacement algorithms.
- Gain practical experience with Unix/Linux system programming.

---

## 🧪 List of Experiments

| Week | Experiment |
|------|------------|
| 1 | Demonstration of `fork()` System Call |
| 2 | Parent Process Computes Sum of Odd Numbers and Child Process Computes Sum of Even Numbers Using `fork()` |
| 3 | Demonstration of `wait()` System Call |
| 4 | Implementation of Orphan Process and Zombie Process |
| 5 | Implementation of Pipe |
| 6 | Implementation of FIFO / Named Pipe |
| 7 | Implementation of Message Queue |
| 8 | Implementation of Shared Memory |
| 9 | Implementation of First-Come, First-Served (FCFS) CPU Scheduling |
| 10 | Implementation of Shortest Job First (SJF) CPU Scheduling |
| 11 | Implementation of Priority Scheduling |
| 12 | Implementation of FIFO Page Replacement Algorithm |
| 13 | Implementation of Least Recently Used (LRU) Page Replacement Algorithm |

### Additional Experiments

- `fork()` and `exec()` system calls
- Implementation of Unix pipeline: `ls | wc`

---

##  Software Requirements

Any Unix/Linux-based operating system can be used, including:

- Ubuntu Linux
- Debian
- Fedora
- Kali Linux
- Linux Mint
- Windows Subsystem for Linux (WSL)

### Compiler

The programs are written in **C** and can be compiled using the **GNU Compiler Collection (GCC)**.

Check GCC installation:

```bash
gcc --version
```

---

## ⚙️ Compilation and Execution

Compile a C program using:

```bash
gcc -Wall -Wextra program.c -o program
```

Run the executable using:

```bash
./program
```

Example:

```bash
gcc -Wall -Wextra fork_demo.c -o fork_demo
./fork_demo
```

---


##  Course Coordination

**Dr. Siddhant Thapliyal**  
Assistant Professor  
Department of Computer Science and Engineering  
Graphic Era Deemed to be University, Dehradun

---
