## Process management

🛑 Process - Process is an active entity that requires a set of resources including a processor, program counter, registers to perform its function.
            - Process means the execution of program
            
🛑 States of process - The states of process is defined in part the current activity of that process.

    New - The process is being created.
    ⬇ 
    Running - Instructions are being executed
    ⬇
    waiting - The process is waiting for some event to occur
    ⬇
    Ready - The process is waiting to the assigned to a process
    ⬇ 
    Terminated - The process has finished execution
    
![states](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Operating%20System/images/process-state.webp)    
## Process control block :- 
  - Each process is reprented in the operating system by a process control block(PCB) also called as task block. It contains many piece of information associated with a specific process.

🔰 Process State
- This specifies the process state i.e. new, ready, running, waiting or terminated.

🔰 Process Number
- This shows the number of the particular process.

🔰 Program Counter
- This contains the address of the next instruction that needs to be executed in the process.

🔰 Registers
- This specifies the registers that are used by the process. They may include accumulators, index registers, stack pointers, general purpose registers etc.

🔰 List of Open Files
- These are the different files that are associated with the process

🔰 CPU Scheduling Information
- The process priority, pointers to scheduling queues etc. is the CPU scheduling information that is contained in the PCB. This may also include any other scheduling parameters.

🔰 Memory Management Information
- The memory management information includes the page tables or the segment tables depending on the memory system used. It also contains the value of the base registers, limit registers etc.

🔰 I/O Status Information
- This information includes the list of I/O devices used by the process, the list of files etc.

🔰 Accounting information
- The time limits, account numbers, amount of CPU used, process numbers etc. are all a part of the PCB accounting information.

🔰 Location of the Process Control Block
- The process control block is kept in a memory area that is protected from the normal user access. This is done because it contains important process information. Some of the operating systems place the PCB at the beginning of the kernel stack for the process as it is a safe location.

![PCB](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Operating%20System/images/PCB%20in%20Operating%20System.png?raw=true)
    
[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Operating%20System/05%20-%20Threads.md)
