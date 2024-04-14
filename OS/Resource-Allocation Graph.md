Created: April-14-2024

[[Deadlock|Deadlocks]] can be described more precisely in terms of a directed graph called *system resource-allocation graph*

The graph consists of a set of vertices V and a set of edges E

Set of Vertices V is then partitioned into two types of nodes:

P = { $P_1, P_2, ..., P_n$ } the set consisting of all active processes

R = { $R_1, R_2, ..., R_n$ } the set consisting of all resource types

Edges are also of 2 types:

*Request Edge* is a directed edge from process $P_i$ to resource type $R_j$ also denoted as $P_i \longrightarrow R_j$ signifies that process $P_i$ has requested an instance of resource type $R_j$ and is currently waiting for that resource

*Assignment Edge* is a directed edge from resource type $R_j$ to process $P_i$ also denoted as $R_j \longrightarrow P_i$ signifies that an instance of resource type $R_j$ has been allocated to process $P_i$

Processes are represented using circles

Resources are denoted using circles

Instances within resources are denoted using dots

![[Resource Allocation Graph.excalidraw]]

If the graph contains no cycles, then no process in the system is deadlocked

If the graph contains a cycle, then a [[Deadlock]] may exist

**Claim Edge** $P_i \longrightarrow R_j$ indicates that process $P_i$ may request resource $R_j$ sometime in future (we'll discuss more about this in [[Resource-Allocation Graph Algorithm]])

# Related Notes

1. [[Operating System]]
# References

1. 