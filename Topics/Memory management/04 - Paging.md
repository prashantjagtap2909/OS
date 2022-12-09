
## Paging 
- Paging is a storage mechanism that allows OS o retrive processes from the secondary storage into the main memory in the form of pages.
- In this paging method , the main memory is divided into small fixed size blocks of physical memory, which is called frames.
- The size of frames should be kept the same as that of a page to have maximum utilization of the main memory and to avoid external fragmentation.
- Paging is used for faster occur to data and it is logical concept

### Paging protection
- The paging process should be protected by using the concept of insertion of an additional bit called valid/invalid bit. 
- Paging memory protection in paging is achieved by associating protection bit with each page.
- These bits are associated with each page table entry and specify protection on the corresponding page.

#### Advantages:
- Easy to use memory management algorithm
- No need for external fragmentation 
- Swapping is easy between equal sized page and page frames

#### Disadvantages:
- May cause internal fragmentation 
- Complex memory management algorithm
- Page table cosume additional memory 
- Multi-level paging may lead to memory reference overhead.



#### Hardware support for paging
- A set of dedicated registers, holding base address of frames.
- In memory page table with a page base register(PTBR).


[next point](https://github.com/prashantjagtap2909/OS/blob/main/Topics/Memory%20management/05%20-%20Segmentation.md)
