## Concurrency 
- It is execution of multiple process at the same time.
- Concurrent access to the shared data may result in data inconsistency. Maintaining data consistency requires mechanisms to ensure the orderly execution of coperating processes.
- Concurrency arises in the same way at different level of execution streams.
- Concurrency in different type of operating systems:
   -  1. Concurrency in multithreading: An interaction between multiple thread running in one process.
   -  2. Concurrency in multiprogramming; An interaction between multiple processes in running on one CPU.
   -  3. Concurrency in multiprocessors: An interaction between multiple CPUs running multiple process or thread.
   -  4. Concurrency in multi-computers: An interaction between multiple computer running distributed processes or thread.

## Critical section 
- The segment of code or the program which tries to access or modify the value of the variables in a shared resource is called critical section

- Critical Section is the part of a program which tries to access shared resources. That resource may be any resource in a computer like a memory location, Data structure, CPU or any IO device.

- The critical section cannot be executed by more than one process at the same time; operating system faces the difficulties in allowing and disallowing the processes from entering the critical section.

- The critical section problem is used to design a set of protocols which can ensure that the Race condition among the processes will never arise.

## Race Condition
- It occurs when two or more operation occur in an undefined manner. When two or more processes are reading or writing some shared data and final result depends on who runs precisely when, are called race condition.

- There is a race condition if the outcome depends on the order of the execution. The outcome depends on the CPU scheduling or interleaving of the thread.

## Mutual Exclusion
- Mutual exclusion methods are used in concurrent programming to avoid the simultaneous use of a common resource, such as a global variable, by piece of computer code called critical sections.

### Requirement of mutual exclusion

   - Mutual exclusion should be ensured in the middle of different processes when accessing shared resources. There must not be two processes within their critical sections at any time.
   
   - Assumptions should not be made as to the respective speed of the unstable processes.
   
   - The process that is outside the critical section must not interfere with another for access to the critical section.
   
   - When multiple processes access its critical section, they must be allowed access in a finite time, i.e. they should never be kept waiting in a loop that has no limits.


## Synchronization - 
- Synchronization is the way by which processes that share the same memory space are managed in an operating system. It helps maintain the consistency of data by using variables or hardware so that only one process can make changes to the shared memory at a time.


[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Synchronization%20and%20Concurrency%20control/02%20-%20Semaphore.md)

