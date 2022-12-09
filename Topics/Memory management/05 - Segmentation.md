
## Segmentation
- A process is divided into Segments. The chunks that a program is divided into which are not necessarily all of the same sizes are called segments. Segmentation gives the user’s view of the process which paging does not give. Here the user’s view is mapped to physical memory.


### 🛑 Types of segmentation

- ⏺ Virtual memory segmentation – Each process is divided into a number of segments, not all of which are resident at any one point in time.

- ⏺ Simple segmentation – Each process is divided into a number of segments, all of which are loaded into memory at run time, though not necessarily contiguously.

### Advantages:
- ⏹ No Internal fragmentation.
- ⏹ Segment Table consumes less space in comparison to Page table in paging.
- ⏹ As a complete module is loaded all at once, segmentation improves CPU utilization.
- ⏹ The user’s perception of physical memory is quite similar to segmentation. Users can divide user programmes into modules via segmentation. These modules are nothing more than the separate processes’ codes.
- ⏹ The user specifies the segment size, whereas in paging, the hardware determines the page size.
- ⏹Segmentation is a method that can be used to segregate data from security operations.


### Disadvantages:
- ⏹ It increases hardware cost 
- ⏹ It increases processor overhead
- ⏹ Danger of thrashing


### Difference between Paging and Segmentation

![image](https://user-images.githubusercontent.com/93985255/206744519-477f2282-4927-40bf-a095-346948ec0da1.png)

[next point]()
