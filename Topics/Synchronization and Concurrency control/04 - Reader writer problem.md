## Reader Writer problem 
- The readers-writers problem relates to an object such as a file that is shared between multiple processes. Some of these processes are readers i.e. they only want to read the data from the object and some of the processes are writers i.e. they want to write into the object.

- The readers-writers problem is used to manage synchronization so that there are no problems with the object data. For example - If two readers access the object at the same time there is no problem. However if two writers or a reader and writer access the object at the same time, there may be problems.

- To solve this situation, a writer should get exclusive access to an object i.e. when a writer is accessing the object, no reader or writer may access it. However, multiple readers can access the object at the same time.

- This can be implemented using semaphores. The codes for the reader and writer process in the reader-writer problem are given as follows −

 #### -🛑 Reader Process
 
   ⏹ The code that defines the reader process is given below −

       -wait (mutex);
       
        rc ++;
        
        if (rc == 1)
        
        wait (wrt);
        
        signal(mutex);
        
        .
        
        .    READ THE OBJECT
        
        .
        
        wait(mutex);
        
        rc --;
        
        if (rc == 0)
        
        signal (wrt);
        
        signal(mutex);
        
        
- In the above code, mutex and wrt are semaphores that are initialized to 1. Also, rc is a variable that is initialized to 0. The mutex semaphore ensures mutual exclusion and wrt handles the writing mechanism and is common to the reader and writer process code.

- The variable rc denotes the number of readers accessing the object. As soon as rc becomes 1, wait operation is used on wrt. This means that a writer cannot access the object anymore. After the read operation is done, rc is decremented. When re becomes 0, signal operation is used on wrt. So a writer can access the object now.

#### -🛑 Writer Process

   ⏹ The code that defines the writer process is given below:

      wait(wrt);
      
      .
      
      . WRITE INTO THE OBJECT

      .

      signal(wrt);
      
      
- If a writer wants to access the object, wait operation is performed on wrt. After that no other writer can access the object. When a writer is done writing into the object, signal operation is performed on wrt.

[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Synchronization%20and%20Concurrency%20control/05%20-%20Monitor.md)
