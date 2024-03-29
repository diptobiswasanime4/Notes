Created: March-22-2024

We have 2 kinds of threads:

1. User threads - Supported above the [[Kernel]] and are managed without Kernel support
2. Kernel threads - Supported and managed directly by the OS

There must exist a relationship between the User threads and the Kernel threads for the system to work together
## Multithreading Models

There are 3 common ways of establishing relationship between User threads and Kernel threads:

1. Many-to-One model
2. One-to-One model
3. Many-to-Many model
### Many-to-One Model

1. Maps many user threads to one kernel thread
2. Thread management is done by the thread library in user space
3. Entire process will block if a thread makes a blocking system call
4. Because only one thread can access the [[Kernel]] at a time, multiple threads are unable to run in parallel on [[Multiprocessor|Multiprocessors]]
### One-to-One Model


### Many-to-Many Model
# Related Notes

1. [[Operating System]]
# References

1. 