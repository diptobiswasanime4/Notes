Created: March-22-2024

If a system contains n processes {P0, P1, ... , Pn} each process has a segment of code, called a **critical section** where the process could be changing values of common variables, writing a file, etc.

So when one process is executing in its critical section, no other process is allowed to execute in its critical section.

The critical-section problem is about designing a [[Protocol]] that processes can use to cooperate and [[Process Synchronization]] can be maintained
## Rules

1. Process must request permission before entering its critical section
2. Section of Code implementing this request is the entry section
3. Critical section maybe followed by an exit section
4. The remaining code is the remainder section

		do {
			Entry section
				Critical section
			Exit section
				Remainder section
		} while (True)
## Requirements

1. Mutual exclusion
2. Progress
3. Bounded waiting
# Related Notes

1. [[Operating System]]
# References

1. 