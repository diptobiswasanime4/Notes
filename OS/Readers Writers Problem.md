Created: March-22-2024

- Database is to be shared among concurrent processes
- Some processes only want to read, we call them as **Readers**
- Other process only want to write, we call them as **Writers**
- Some processes want to do both
## Problem

- If two readers want to read from the DB there is no problem
- But if one process wants to read, and the other wants to write, or both wants to write, there could be chaos

To ensure such difficulties do not arise we require that writes have exclusive access to the shared database

This synchronization problem is called as the **Readers-Writers Problem**
## Solution Using Semaphores

We will make use of two [[Semaphores|semaphores]] and an integer variable:

1. **mutex**, a semaphore (initialized to 1) is used to ensure mutual exclusion when **readcount** is updated, i.e. any reader enters or exit from critical section
2. **wrt**, a semaphore (initialized to 1) is common to both reader and writer processes
3. **readcount**, an integer variable (initialized to 0) keeps track of how many processes are currently reading the object.
# Related Notes

1. [[Operating System]]
2. [[Process Synchronization]]
# References

1. 