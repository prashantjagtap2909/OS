## Fragmentation
- Fragmentation is an unwanted problem in the operating system in which the processes are loaded and unloaded from memory, and free memory space is fragmented.


#### Types of Fragmentation

- 1. External fragmentation 
  - When the free memory blocks available in memory are too small and even non-contiguous.

  ![image](https://user-images.githubusercontent.com/93985255/206718989-16a9098b-511b-48a7-92a1-26c3e0dde8f5.png)


- 2. Internal fragmentation
  - It occurs when the process does not fully utilize the memory allocate to it.

  ![image](https://user-images.githubusercontent.com/93985255/206719031-0ce62cd8-0be8-4e07-af8b-86665a72a3d3.png)


## Advantages


⏺ Fast Data Writes

- Data write in a system that supports data fragmentation may be faster than reorganizing data storage to enable contiguous data writes.

⏺ Fewer Failures

- If there is insufficient sequential space in a system that does not support fragmentation, the write will fail.

⏺ Storage Optimization

- A fragmented system might potentially make better use of a storage device by utilizing every available storage block.


## Disadvantages


⏺ Need for regular defragmentation


- A more fragmented storage device's performance will degrade with time, necessitating the requirement for time-consuming defragmentation operations.

⏺ Slower Read Times

- The time it takes to read a non-sequential file might increase as a storage device becomes more fragmented.
  

[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Memory%20management/03%20-%20Buddy%20System.md)
