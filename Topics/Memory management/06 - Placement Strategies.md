## Memory allocation algorithm

- 1. First fit
  
  - First Fit algorithm scans the linked list and whenever it finds the first big enough hole to store a process, it stops scanning and load the process into that hole. This procedure produces two partitions. Out of them, one partition will be a hole while the other partition will store the process.
  
  - First Fit algorithm maintains the linked list according to the increasing order of starting index. This is the simplest to implement among all the algorithms and produces bigger holes as compare to the other algorithms.
  


- 2. Best Fit Algorithm

  - The Best Fit algorithm tries to find out the smallest hole possible in the list that can accommodate the size requirement of the process.

  - It is slower because it scans the entire list every time and tries to find out the smallest hole which can satisfy the requirement the process.
  - Due to the fact that the difference between the whole size and the process size is very small, the holes produced will be as small as it cannot be used to load any process and therefore it remains useless.
    Despite of the fact that the name of the algorithm is best fit, It is not the best algorithm among all.


- 3. Worst Fit Algorithm

  - The worst fit algorithm scans the entire list every time and tries to find out the biggest hole in the list which can fulfill the requirement of the process.

  - Despite of the fact that this algorithm produces the larger holes to load the other processes, this is not the better approach due to the fact that it is slower because it searches the entire list every time again and again.


[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Memory%20management/07%20-%20Virtual%20Memory.md)
