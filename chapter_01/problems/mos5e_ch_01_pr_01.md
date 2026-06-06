# MOS5E Chapter 1 Problem 1

## About

This note contains my solution to Problem 1 from Chapter 1 of *Modern Operating Systems (5th Global Edition)*.

## Problem

*Problem statement omitted to respect the publisher's copyright.*

## Solution

An operating system provides two main functions:

1. **Hardware abstraction** -
   A computer will hold hardware that requires dedicated drivers for each type and generation of hardware. The operating system hides the complexity of the underlying hardware by providing higher-level abstractions. Tanenbaum and Bos describe this view of the operating system as an *extended machine*. Applications interact with these abstractions rather than directly controlling hardware devices. The operating system reduces the cognitive load of the application-level developers with the intention to make it faster to both develop new applications as well as porting applications to new hardware.
2. **Resource management** -
   The operating system manages and allocates hardware resources such as CPU time, memory, storage, and I/O devices among competing processes. This allows multiple applications to execute concurrently while minimizing unwanted interference.

It is not possible to say that one function is more important than the other, what provides the highest value will depend on the situation and view-point.

## Answer

The two main functions of an operating system are (1) hardware abstraction and (2) resource management.

## References

Tanenbaum, A. S., & Bos, H. (2024). *Modern operating systems* (5th Global ed.). Pearson Educated Limited.

## 🏷 Tags

#operating-systems #mos5e
