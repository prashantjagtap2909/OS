## Dining philosopher 
- The dining philosophers problem states that there are 5 philosophers sharing a circular table and they eat and think alternatively. There is a bowl of rice for each of the philosophers and 5 chopsticks. A philosopher needs both their right and left chopstick to eat. A hungry philosopher may only eat if there are both chopsticks available.Otherwise a philosopher puts down their chopstick and begin thinking again.

- The dining philosopher is a classic synchronization problem as it demonstrates a large class of concurrency control problems


### 🛑 Solution of Dining Philosophers Problem

- A solution of the Dining Philosophers Problem is to use a semaphore to represent a chopstick. A chopstick can be picked up by executing a wait operation on the semaphore and released by executing a signal semaphore.

- The structure of the chopstick is shown below −

      - semaphore chopstick [5];
     
  
    
- Initially the elements of the chopstick are initialized to 1 as the chopsticks are on the table and not picked up by a philosopher.

- The structure of a random philosopher i is given as follows −

      do {
        wait( chopstick[i] );
        wait( chopstick[ (i+1) % 5] );
        . .
        . EATING THE RICE
        .
         signal( chopstick[i] );
         signal( chopstick[ (i+1) % 5] );
        .
        . THINKING
        .
      } while(1);
      
      
- In the above structure, first wait operation is performed on chopstick[i] and chopstick[ (i+1) % 5]. This means that the philosopher i has picked up the chopsticks on his sides. Then the eating function is performed.

- After that, signal operation is performed on chopstick[i] and chopstick[ (i+1) % 5]. This means that the philosopher i has eaten and put down the chopsticks on his sides. Then the philosopher goes back to thinking.

[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Synchronization%20and%20Concurrency%20control/08%20-%20Deadlock%20and%20its%20principle.md)
