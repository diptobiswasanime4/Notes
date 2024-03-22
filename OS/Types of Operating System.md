Created: March-22-2024

There are several types of Operating Systems, created to address several use cases.
## Number of General Purpose Processors

1. Single Processor Systems
2. Multiprocessor Systems
3. Clustered Systems
### Single Processor Systems

- One main CPU is capable of executing a general purpose instruction-set including instructions from user processes.
- Other special purpose processors could be present, which performs device specific tasks
### Multiprocessor Systems

- Has two or more processors in close communication, sharing computer bus and sometimes the clock, memory and peripheral devices
- Also called Parallel Systems or [[Tightly Coupled Systems]]
- Advantages:
	1. Increased throughput
	2. Economy of scale
	3. Increased reliability - if one processor fails, others will back it up
- Types:
	1. Symmetric Multiprocessing - processors are parallel
	2. Asymmetric Multiprocessing - one processor is master, others are slaves, follows [[Master-Slave Architecture]]
### Clustered Systems

- Like to Multiprocessor systems, Clustered systems gather multiple [[CPU|CPUs]] for computational work
- Unlike Multiprocessor systems, Clustered systems consist of two or more individual systems
- Provides high availability
- Can be symmetric and asymmetric, like Multiprocessor Systems
# Related Notes

1. [[Operating System]]
# References

1. 