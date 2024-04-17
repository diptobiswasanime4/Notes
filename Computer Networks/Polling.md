Created: April-17-2024

- Polling requires one of the nodes to be designated as the Master Node or Primary Station
- Master node polls each of the nodes in a round-robin fashion
- This process continues, and each node sends data
## Drawbacks

- There is delay in the amount of time required to notify a node
- If the Master Node fails the entire channel becomes inoperative
## Functions

1. **Poll function** - If the Primary Station wants to receive data it asks secondaries if they have anything to send
2. **Select function** - If the Primary Station wants to send data, it tells secondary to get ready to receive
## Efficiency



# Related Notes

1. [[Computer Network]]
# References

1. 