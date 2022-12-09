## Page replacement 
- This allow us too get n=more no. of process into the memory at the same time.
-But what happen when a proces request for more pages and no free memory is avilable to bring them in following steps can e taken to deal with this problem:-
  - 1. Put the process in the wait queue, until any other process finishes its execution thereby freeing frames.
  - 2. Or remove some other process completely from the memory to free frames.
  - 3. Or find some pages that are being used right now, move them to the disk to get free frames. this technique is called *Page replacement* and is most commonly used.

## Types of Page replacement algorithm

🛑 FIFO:
    - A very simple way of page replacement is FIFO (first in first out).
    - As new page are required and are swaapped in, they are added to tail of queue and the page which is at the head become the victim.
    - It is an effective way of page replacement but can be used for small system.
    
    
    
🛑 Optimal page replacement:
    - The algorithm that has the lowest page fault rate of all algorithms and will never suffer from belady's anomaly. Such an alorithm does exist and has been called OPT or MIN.
    - Replace the page that will not been used for longest period of time.
    - Use of this page replacemet algorithm gurantee the lowest possible page fault for a fixed number of frames.
    
    
🛑 LRU:
      - If the optimal algorithm is not feasible, perhaps an approximation of the optimal is possible.
      - The key distinct between the FIFO and OPT algorithm is that FIFO algorithm uses the time when a page was brought into memory, whereas the OPT algorithm uses the time when a page is to be used.
      - If using the recent past an approximation of the near future, then one can replace the page that has not been used for the longest period of time. This approach is the least recently used(LRU) agorithm.
      
### Example
![image](https://user-images.githubusercontent.com/93985255/206761033-f8be1550-8800-4be9-9ae9-c2ebea2bcd1d.png)
![image](https://user-images.githubusercontent.com/93985255/206761120-1c1b2719-9041-458f-96cd-88e7ebb533d1.png)
![image](https://user-images.githubusercontent.com/93985255/206761169-e0dd4426-73a2-4dbb-839e-c201e79367c2.png)


[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Memory%20management/10%20-%20Thrashing.md)
