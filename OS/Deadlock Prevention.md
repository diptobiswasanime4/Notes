Created: April-14-2024

For a [[Deadlock]] to occur we have to make sure 1 of the 4 necessary conditions mustn't occur:

1. Mutual exclusion
2. Hold and wait
3. No pre-emption
4. Circular wait

**Mutual exclusion** must hold for non-sharable resources. Example - Printer

Sharable resources on the other hand doesn't require mutually exclusion. Example - Read-only files

In general, however, we cannot avoid deadlocks by denying **mutual exclusion** because some resources are intrinsically non-sharable.

# Related Notes

1. [[Operating System]]
2. [[Deadlock Characterization]]
# References

1. 