## Monitor

- Monitors are a programming language component that aids in the regulation of shared data access. The Monitor is a package that contains shared data structures, operations, and synchronization between concurrent procedure calls. Therefore, a monitor is also known as a synchronization tool. Java, C#, Visual Basic, Ada, and concurrent Euclid are among some of the languages that allow the use of monitors. Processes operating outside the monitor can't access the monitor's internal variables, but they can call the monitor's procedures.

- For example, synchronization methods like the wait() and notify() 

![image](https://user-images.githubusercontent.com/93985255/206481773-1eb448ee-3130-4f65-b11e-33edc9e1808e.png)



### π Characteristics of Monitors 


π° We can only run one program at a time inside the monitor.

π° Monitors in an operating system are defined as a group of methods and fields that are combined with a special type of package in the os.

π° A program cannot access the monitor's internal variable if it is running outside the monitor. Although, a program can call the monitor's functions.

π° Monitors were created to make synchronization problems less complicated.

π° Monitors provide a high level of synchronization between processes.




### π  Advantages of monitors

π° Monitors offer the benefit of making concurrent or parallel programming easier and less error-prone than semaphore-based solutions.

π° It helps in process synchronization in the operating system.

π° Monitors have built-in mutual exclusion.

π° Monitors are easier to set up than semaphores.

π° Monitors may be able to correct for the timing faults that semaphores cause.




### π  Disadvantages of Monitors

π° Monitors must be implemented with the programming language.

π°Monitor increases the compiler's workload.

π°The monitor requires to understand what operating system features are available for controlling crucial sections in the parallel procedures.


[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Synchronization%20and%20Concurrency%20control/06%20-%20Producer%20consumer%20problem.md)
