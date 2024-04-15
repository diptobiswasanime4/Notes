Created: April-15-2024

$P_1$ makes a request for data A from [[Main Memory]]

Initial request will be a Compulsory Miss

When the Data A is loaded it will be marked as Shared S

If Data A is changed it will be marked as Modified M

$P_1$ will then send an Invalid response across the Shared Bus to invalidate any old copies of Data A in any other processors

- Write invalidate
	- Write Through
	- Write Back

When a Processor $P_i$ wants to update A but the Data is in Invalid State, it won't be able to perform the action. This is called *Coherence Miss*

Processors $P_2, P_3, P_4$ will be Snooping on the Shared Bus at all times, and hence Cache Coherency is maintained

![[Processors.excalidraw]]
## Limitations

Snooping-based protocol is fine for a low-number of processors

For a high-number of processors the Shared Bus will be overcrowded with a large number of broadcast requests

# Related Notes

1. [[Computer Architecture]]
2. [[Computer Organization]]
# References

1. 