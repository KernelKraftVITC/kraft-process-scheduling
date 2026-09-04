---
author: Krishdeep13
updated: 2026-09-04
---

# M4: Process & Scheduling

Introduce true multitasking: kernel threads, context switching, a scheduler, and the transition into unprivileged user mode.

## Core objectives

- Thread abstraction and context switch
- Round-robin scheduler
- Ring-3 user mode transition

## Architecture

Pending implementation details.

## References

- [OSDev Wiki — Kernel Multitasking](https://wiki.osdev.org/Kernel_Multitasking)
- [OSDev Wiki — Context Switching](https://wiki.osdev.org/Context_Switching)
- [OSDev Wiki — Scheduling Algorithms](https://wiki.osdev.org/Scheduling_Algorithms)
- [Linux kernel source — kernel/sched/core.c](https://github.com/torvalds/linux/blob/master/kernel/sched/core.c)
- [Linux kernel source — arch/x86/kernel/process_64.c](https://github.com/torvalds/linux/blob/master/arch/x86/kernel/process_64.c)
- [Linux From Scratch](https://www.linuxfromscratch.org/lfs/view/stable/)

LFS assumes a working kernel and scheduler already exist — it's not a reference for building one. Included for general context only; OSDev and the Linux kernel source are what actually apply here.
