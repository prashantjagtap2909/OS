## 🛑 Deadlock Avoidance:

In Deadlock Avoidance, the system will be checked if it is in a safe state or an unsafe state. Safe state is ensured when the request for the resource by the process is permitted when there is no deadlock found in the system. If there is deadlock found then the system will be in an unsafe state.



## ♦ Disadvantage:

- It has a fixed number of processes and resources that are required while executing. 
 
- No other processes can be executed in the middle and also any resource cannot be allocated to another process until deadlock arrives.
 
- Maximum resources that are acquired for the processes should be known and allocated in advance.
 
- In Banker’s Algorithm, all resources can be requested for a certain amount of time but the time is one year.
 
- So these processes which are acquiring resources can release those resources after that certain amount of time, until then remaining processes should wait for the acquisition of resources. This is the starvation problem. 

[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Synchronization%20and%20Concurrency%20control/11%20-%20Deadlock%20Detection.md)
