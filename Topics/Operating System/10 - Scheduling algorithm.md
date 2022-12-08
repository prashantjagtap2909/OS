##  Scheduling algorithm

- A Process Scheduler schedules different processes to be assigned to the CPU based on particular scheduling algorithms

### 🛑 First Come First Serve (FCFS)
 - Jobs are executed on first come, first serve basis.
 - It is a non-preemptive, pre-emptive scheduling algorithm.
 - Easy to understand and implement.
 - Its implementation is based on FIFO queue.
 - Poor in performance as average wait time is high.

![image](https://user-images.githubusercontent.com/93985255/206348041-58376726-471f-40b0-946f-3a906f087627.png)





### 🛑 Shortest Job First (SJF)
 - This is a non-preemptive, pre-emptive scheduling algorithm.
 - Best approach to minimize waiting time.
 - Easy to implement in Batch systems where required CPU time is known in advance.
 - Impossible to implement in interactive systems where required CPU time is not known.
 - The processer should know in advance how much time process will take.

![image](https://user-images.githubusercontent.com/93985255/206348162-d9d3acf4-bfaf-4ab6-8f60-5d9902e559f8.png)
![image](https://user-images.githubusercontent.com/93985255/206348394-6b22be64-09c2-42ce-9e4b-5ac2475ae944.png)




### 🛑 Round Robin Scheduling
 - Round Robin is the preemptive process scheduling algorithm.
 - Each process is provided a fix time to execute, it is called a quantum.
 - Once a process is executed for a given time period, it is preempted and other process executes for a given time period.
 - Context switching is used to save states of preempted processes.

![image](https://user-images.githubusercontent.com/93985255/206349239-8be26abb-eed7-45d6-8ae7-037436448c90.png)



### 🛑 Priority Based Scheduling
 - Priority scheduling is a non-preemptive algorithm and one of the most common scheduling algorithms in batch systems.
 - Each process is assigned a priority. Process with highest priority is to be executed first and so on.
 - Processes with same priority are executed on first come first served basis.
 - Priority can be decided based on memory requirements, time requirements or any other resource requirement.

![image](https://user-images.githubusercontent.com/93985255/206348698-fb25ab6f-d620-47b2-9e9b-c8217349890c.png)
![image](https://user-images.githubusercontent.com/93985255/206348890-8a42e710-cca3-49ac-8bbd-3a289d102a0f.png)





[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Operating%20System/11%20-%20Imp%20questions.md)
