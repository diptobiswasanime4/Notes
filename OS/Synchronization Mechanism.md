Created: May-03-2024

Below are the requirements of Synchronization Mechanism

1. Primary
	1. Mutual exclusion
	2. Progress
2. Secondary
	1. Bounded waiting
	2. Portability or Architectural neutrality
## Mutual Exclusion

If one process is in [[Critical Section]] other process shouldn't be allowed into
## Progress

If a process doesn't want to get into [[Critical Section]] that's fine, but it shouldn't block other process from doing so.
## Bounded Waiting

If a process wants to get into [[Critical Section]] it shouldn't wait forever

There should be a finite bound on the waiting time

We should think of when a process will enter Critical Section
## Portability or Architectural Neutrality

Synchronization mechanism should work on all [[Hardware]] and OS
## Critical Section is Occupied

When [[Critical Section]] is occupied another process can:

1. Continuously check to get into the CS, this is called Busy waiting
2. Wait till completion, not Busy waiting

Hence Synchronization Mechanism can be divided into:

1. With [[Busy Waiting]]
2. Without Busy Waiting

# Related Notes

1. [[Operating System]]
# References

1. 