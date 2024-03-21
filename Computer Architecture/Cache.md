Created: March-20-2024

There are 3 levels of Cache memory:

1. Level 1 Cache (L1) - smallest but fastest
2. Level 2 Cache (L2)
3. Level 3 Cache (L3)
### Cache Hit

During execution if the processor is able to find the required info, it is called **Cache Hit**

The time required by is called **Hit Latency**

The [[Data Structure]] used to find the information is called Tag Directory

If the info is absent in the cache, we call it **Cache Miss**. In this case the processor will seek info from the next-level of memory, that is the [[Main Memory]]. This is called **Page Hit**

The time taken by the entire process is called **Miss Latency**

Now if the info is absent even in the Main memo, we call it **Page Fault**

Lastly the process will try to find the info from the [[Secondary Memory|Secondary storage]]. This entire process is called **Page Fault Service** and the time taken is called **Page Fault Service Time**
## Locality of Reference

Locality of Reference determines which data of the Main memory should be kept in the cache.

There are 2 approaches:

1. Spatial Locality - If a memo location is referred before, nearby locations maybe referred
2. Temporal Locality - If a memo location is referred, there is a sound possibility that it'll be referred again
# Related Notes

1. [[Computer Architecture]]
2. [[Computer Organization]]
# References

1. 