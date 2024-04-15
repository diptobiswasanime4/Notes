Created: April-15-2024

Cache replacement policies are essential for Block Replacement phase:

1. Random Replacement
2. FIFO
3. LIFO
4. Optimal Replacement (Belady's Optimal Algorithm)
5. Most Recently Used (MRU)
6. Least Recently Used (LRU)
## Random Replacement

- Evict any block from [[Cache]] at random
- Access info is not required
- Not implemented anymore (used to be implemented in [[ARM]])
## FIFO

- Evicts blocks from cache in their order of arrival
- Cache behaves like a [[Queue]]
## LIFO

- Evicts the most recently added block
- Cache behaves like a [[Stack]]
## Optimal Replacement

- Evicts block that won't be referred for the longest period of time
- Prediction of block requests is impossible


# Related Notes

1. [[Computer Architecture]]
2. [[Computer Organization]]
# References

1. 