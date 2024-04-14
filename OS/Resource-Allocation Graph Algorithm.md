Created: April-14-2024

**Claim Edge** $P_i \longrightarrow R_j$ indicates that process $P_i$ may request resource $R_j$ sometime in future

It is represented by a dashed line

![[Resource Allocation Graph Algo.excalidraw]]

When process $P_i$ requests resource $R_j$ the claim edge $P_i \longrightarrow R_j$ is converted to a request edge

When resource $R_j$ is released by $P_i$ the assignment edge $R_j \longrightarrow P_i$ is reconverted to a claim edge $P_i \longrightarrow R_j$

The request can be granted only if doing so will not form a cycle in the graph

When no cycle forms we're in a **safe state** and there is no possibility of a [[Deadlock]]

When cycle forms we're in **unsafe state** and there is a possibility of a [[Deadlock]]

# Related Notes

1. [[Operating System]]
2. [[Resource-Allocation Graph]]
# References

1. 