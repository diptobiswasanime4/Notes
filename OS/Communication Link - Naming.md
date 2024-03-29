Created: March-22-2024

Processes that want to communicate must have a way to refer each other.

They can use direct or indirect communication for this purpose.
## Direct Communication

In **direct communication** each process that wants to communicate must explicitly name the recipient or sender of the communication

A link is established automatically between every pair of processes that want to communicate, the processes only need to know each others identities

This scheme exhibits symmetry in addressing, both the sender and receiver process must name the other to communicate

Another variant of **direct communication** is where only the sender names the recipient, the recipient is not required to name the sender. This scheme exhibits asymmetry.

The *disadvantage* of both kinds of **direct communication** is the limited modularity of the resulting process definitions, i.e. changing the identifier of a process may necessitate examining all other process definitions.
## Indirect Communication

The messages are sent to and from a mailbox or [[Port]]

- A mailbox can be viewed as an object into which messages can be placed by processes, and removed
- Each mailbox has a unique id
- Two processes can communicate only if the processes have a shared mailbox

A [[Communication Link]] in this scheme has the following properties:

1. Link is established between pair of processes only if both members of the pair have a shared mailbox
2. Link may be associated with more than 2 processes
3. Between each pair of communicating processes, there may be a number of different links, with each link corresponding to one mailbox

A mailbox can be owned either by a process or by the Operating System
# Related Notes

1. [[Operating System]]
2. [[Message Passing System]]
# References

1. 