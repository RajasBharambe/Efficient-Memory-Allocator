# Efficient Memory Allocator

## Highlights:
- Designed a simulator for the efficient dynamic allocation of memory to a large number of processes
- Utilized the first-fit strategy to decide the locations at which memory should be allocated
- Requests included are A(Allocate) , D(Deallocate), H(stop), T(Terminate)


## Detailed Statement :

There are n processes and the system has a memory of size M, consisting of locations
with address 0 to M-1. A program may request to be allocated memory of size m,
and we have to allocate a set of m consecutive locations that are currently
not allocated to any program. If they are available, we should find the 
starting address of such a set of m locations, if not, the request
should be kept pending. A program may also request deallocation of memory
that was previously allocated to it. The starting address of the memory
to be deallocated.
