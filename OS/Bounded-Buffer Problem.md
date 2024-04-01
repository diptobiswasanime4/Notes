Created: March-22-2024

The Bounded-Buffer Problem also known as a Producer-Consumer Problem is a Classic Synchronization Problem.

- There is a buffer of n slots and each slot is capable of storing one unit of data
- There are two processes running, namely Producer and Consumer, which are operating on the buffer
- Producer tries to insert data into an empty slot of the buffer
- Consumer tries to remove data from a filled slot of the buffer
### Problems

1. Producer must not insert data when buffer is full
2. Consumer must not remove data when buffer is empty
3. Producer and Consumer should not insert and remove data simultaneously
### Solution

To solve this problem we'll use 3 [[Semaphores|semaphores]]:

1. m (mutex), a binary semaphore used to acquire and release the lock
2. empty, a counting semaphore whose initial value is the number of slots in the buffer, since initially all slots are empty
3. full, a counting semaphore whose initial value is 0
# Related Notes

1. [[Operating System]]
2. [[Buffer]]
# References

1. 