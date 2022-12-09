## Mutual exclusion
- Mutual exclusion in OS is designed so that when a write operation is in the process then another thread is not granted to use the very object before the first one has done writing on the critical section after that releases the object because the rest of the processes have to read and write it.

## Requirements for mutual exclusion

  - Mutual exclusion should be ensured in the middle of different processes when accessing shared resources. There must not be two processes within their critical sections at any time.

  - Assumptions should not be made as to the respective speed of the unstable processes.
  
  - The process that is outside the critical section must not interfere with another for access to the critical section.

  - When multiple processes access its critical section, they must be allowed access in a finite time, i.e. they should never be kept waiting in a loop that has no limits.

![image](https://user-images.githubusercontent.com/93985255/206478083-965d5866-9a46-45aa-9884-059b2e89f235.png)


[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Synchronization%20and%20Concurrency%20control/04%20-%20Reader%20writer%20problem.md)
