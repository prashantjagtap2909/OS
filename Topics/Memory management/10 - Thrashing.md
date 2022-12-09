## Thrashing

- In multiprogramming, there can be a scenario when the system spends most of its time shuttling pages between the main memory and the secondary memory due to frequent page faults. This behavior is known as thrashing.

- A process is said to be thrashing if the CPU spends more time serving page faults than executing the pages. This leads to low CPU utilization and the Operating System in return tries to increase the degree of multiprogramming.
![image](https://user-images.githubusercontent.com/93985255/206761568-f167ae40-2f50-4a37-9747-58d3d3fc8456.png)


### Causes of Thrashing in OS


- High degree of Multiprogramming.
- Less number of frames compared to the processes required.
- The process scheduling scheme which swaps in more processes when CPU utilization is low.


[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Memory%20management/11%20-%20Imp%20Questions.md)
