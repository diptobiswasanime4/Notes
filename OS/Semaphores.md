Created: March-22-2024

Semaphore as proposed by Edsger Dijkstra is a technique to manage concurrent processes by using a simple integer value, which is called a semaphore

Semaphore is simply a variable that is non-negative and shared between threads. This variable is used to solve the critical section problem and to achieve process synchronization in the multiprocessing environment.

A semaphore S is an integer variable that, apart from initialization, is accessed only through 2 standard atomic operations: wait () and signal ()

wait () is denoted by P which means "to test"

	P (Semaphore S) {
		while (S <= 0) {
			; // no operation
			S--;
		}
	}

signal () is denoted by V which means "to increment"

	V (Semaphore S) {
		S++;
	}
## Types of Semaphores

1. Binary Semaphore - The value of a binary Semaphore can range between 0 and 1. On some systems Binary semaphores are also known as Mutex locks, as they are locks that provide mutual exclusion.
2. Counting Semaphore - Its value can range over an unrestricted domain. It is used to control access to a resource that has multiple instances.
# Related Notes

1. [[Operating System]]
# References

1. 