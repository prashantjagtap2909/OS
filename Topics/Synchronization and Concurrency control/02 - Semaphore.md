## Semaphore
- Semaphores are integer variables that are used to solve the critical section problem by using two atomic operations, wait and signal that are used for process synchronization.

- Wait
The wait operation decrements the value of its argument S, if it is positive. If S is negative or zero, then no operation is performed.

      - wait(S)
          {
    
           while (S<=0);

           S--;
      
         }
         
- Signal
The signal operation increments the value of its argument S.

        - signal(S)
        {
         S++;
        }
        
## Types of Semaphores
There are two main types of semaphores i.e. counting semaphores and binary semaphores. Details about these are given as follows −

 ♦ Counting Semaphores
  - These are integer value semaphores and have an unrestricted value domain. These semaphores are used to coordinate the resource access, where the semaphore count is the number of available resources. If the resources are added, semaphore count automatically incremented and if the resources are removed, the count is decremented.

♦ Binary Semaphores
  - The binary semaphores are like counting semaphores but their value is restricted to 0 and 1. The wait operation only works when the semaphore is 1 and the signal operation succeeds when semaphore is 0. It is sometimes easier to implement binary semaphores than counting semaphores.

🛑 Advantages of Semaphores

-⏺ Semaphores allow only one process into the critical section. They follow the mutual exclusion principle strictly and are much more efficient than some other methods of synchronization.

-⏺ There is no resource wastage because of busy waiting in semaphores as processor time is not wasted unnecessarily to check if a condition is fulfilled to allow a process to access the critical section.

-⏺ Semaphores are implemented in the machine independent code of the microkernel. So they are machine independent.


🛑 Disadvantages of Semaphores

-⏺ Semaphores are complicated so the wait and signal operations must be implemented in the correct order to prevent deadlocks.

-⏺ Semaphores are impractical for last scale use as their use leads to loss of modularity. This happens because the wait and signal operations prevent the creation of a structured layout for the system.

-⏺ Semaphores may lead to a priority inversion where low priority processes may access the critical section first and high priority processes later.
