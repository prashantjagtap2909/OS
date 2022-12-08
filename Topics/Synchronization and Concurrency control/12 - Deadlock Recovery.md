## Deadlock recovery
- Deadlock recovery occurs when a deadlock is detected. When a deadlock is detected, our system stops working, and when the deadlock is resolved, our system resumes operation.

- As a result, after detecting deadlock, a method or way must be required to recover that deadlock in order to restart the system. The technique is known as deadlock recovery.


### Deadlock recovery methods
 ♦ Resource Preemption
- The ability to take a resource away from a process, have another process use it, and then give it back without the process noticing It is highly dependent on the nature of the resource.

- Deadlock recovery through preemption is too difficult or sometimes impossible.

♦ Recovery through RollBack
- In this case of deadlock recovery through rollback, whenever a deadlock is detected, it is easy to see which resources are needed.

- To recover from deadlock, a process that owns a needed resource is rolled back to a point in time before it acquired some other resource just by starting one of its earlier checkpoints.

♦ Recovery through Killing Processes
- This method of deadlock recovery via killing processes is the most basic method of deadlock recovery.

- Sometimes it is best to kill a process that can be restarted from the beginning with no ill effects.


[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Synchronization%20and%20Concurrency%20control/13%20-%20Imp%20questions.md)
