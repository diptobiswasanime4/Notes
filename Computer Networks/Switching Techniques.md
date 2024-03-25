Created: March-23-2024

Switching helps in deciding the best route for data transmission, in the presence of multiple routes, in a Computer Network.
## Techniques

1. Circuit Switching
2. Message Switching
3. Packet Switching
	1. Datagram Approach
	2. Virtual Circuit Approach
### Circuit Switching

A dedicated path is established between the sender and receiver.

Below is the standard process:

1. Connection establishment
2. Data transfer
3. Disconnection

Example - Telephone Network
### Message Switching

Message is transferred as a complete unit and forwarded using store and forward mechanism at the intermediary node.

Message Switching is not suited for stream media and real-time applications.
### Packet Switching

Message is broken into individual chunks called packets. Each packet will have a source and dest. IP address with sequence number, and is sent individually.

Example - The [[Internet]] is a packet switched network.

Sequence numbers will help the receiver to:

1. Reorder the packets
2. Detect missing packets
3. Send acknowledgements

Packet Switching has 2 apporaches:

1. **Datagram approach**
	- Also called connectionless switching
	- Each independent entity is called a datagram
	- Datagrams contain dest. info and the intermediary devices use this info to forward datagrams toward the right dest.
	- Path is not fixed, intermediate nodes take routing decisions
2. **Virtual Circuit approach**
	- Also called connection-oriented switching
	- Pre-planned route is established before message is sent
	- Call request and call accept packets are used to establish connection between sender and receiver
	- Path is fixed
# Related Notes

1. [[Computer Network]]
# References

1. 