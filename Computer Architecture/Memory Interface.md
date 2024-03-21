Created: March-20-2024

Memory interfacing is generally done in 2 ways.
### Memory levels are parallelly connected to the Processor

![[parallel_memory_excal.excalidraw]]

Tavg. = H1.T1 + (1 - H1).H2.T2 + (1 - H1).(1 - H2).T3

considering only 3 memory units.

**Hit Ratio** is the probability of successfully finding a particular [[Memory|memory resource]]
### Memory levels are connected in series to the processor

![[series_memory_excal.excalidraw]]

Tavg. = H1.T1 + (1 - H1).H2.(T1 +T2) + (1 - H1).(1 - H2).(T1 + T2 + T3)
# Related Notes

1. [[Computer Architecture]]
2. [[Computer Organization]]
# References

1. 