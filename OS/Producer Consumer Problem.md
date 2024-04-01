Created: March-22-2024

A producer process produces information that is consumed by a consumer process.

So what is the problem!?

The problem is that the producer and consumer must work concurrently, so the consumer shouldn't try to consume what is not produced, hence we should find a mechanism to supply the consumer with a buffer of items before the producer produces.

Example - A [[Compiler]] produces [[Assembly Language]] Code, which is consumed by an [[Assembler]]. The Assembler in turn produces object modules which is consumed by the loader.

- One solution to the [[Bounded-Buffer Problem|producer-consumer problem]] uses [[Shared Memory System]]
- To allow producer and consumer processes to run [[Concurrency|concurrently]] we must have available buffer of items that can be filled by the producer and emptied by the consumer
- The buffer will reside in a region of memory that is shared by the producer and consumer processes
- A producer can produce one item while the consumer is consuming another item
- The producer and consumer must be synchronized, so that the consumer doesn't try to consume an item that has not yet been produced
# Related Notes

1. [[Operating System]]
2. [[Buffer]]
# References

1. 