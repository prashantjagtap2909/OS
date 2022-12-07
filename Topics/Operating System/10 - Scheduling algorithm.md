##  Scheduling algorithm

- A Process Scheduler schedules different processes to be assigned to the CPU based on particular scheduling algorithms

#### First Come First Serve (FCFS)
 - Jobs are executed on first come, first serve basis.
 - It is a non-preemptive, pre-emptive scheduling algorithm.
 - Easy to understand and implement.
 - Its implementation is based on FIFO queue.
 - Poor in performance as average wait time is high.


#### Shortest Job First (SJF)
 - This is a non-preemptive, pre-emptive scheduling algorithm.
 - Best approach to minimize waiting time.
 - Easy to implement in Batch systems where required CPU time is known in advance.
 - Impossible to implement in interactive systems where required CPU time is not known.
 - The processer should know in advance how much time process will take.


#### Round Robin Scheduling
 - Round Robin is the preemptive process scheduling algorithm.
 - Each process is provided a fix time to execute, it is called a quantum.
 - Once a process is executed for a given time period, it is preempted and other process executes for a given time period.
 - Context switching is used to save states of preempted processes.


#### Priority Based Scheduling
 - Priority scheduling is a non-preemptive algorithm and one of the most common scheduling algorithms in batch systems.
 - Each process is assigned a priority. Process with highest priority is to be executed first and so on.
 - Processes with same priority are executed on first come first served basis.
 - Priority can be decided based on memory requirements, time requirements or any other resource requirement.


[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Operating%20System/11%20-%20Imp%20questions.md)
