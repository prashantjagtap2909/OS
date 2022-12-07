## Threads :- 
          - A thread is a path of exexution within a process. A process can contain multiple threads. It is also known as light weight process.
          
### Thread lifecycle

🛑 New 
    - Thread is just created.
    
🛑 Ready 
    - Thread's start() method invoked and now it is executing OS put thread into ready state.
    
🛑 Running 
    - Highest priority ready thread enters the running state. Thread is assigned a processor and now is running.
    
🛑 Blocked 
    - This is the state when a thread is waiting for a lock to access the object.
    
🛑 Waiting 
    - Here thread is waiting indefinitely for another thread to perform an action
    
🛑 Sleeping
    - Thread sleep for a specified time of period. When sleeping time expires, it enters to ready state. CPU is not used by sleeping thread.
    
🛑 Dead 
    - When thread completes task or operation





[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Operating%20System/06%20-%20Multithreading%20model.md)
