Created: April-17-2024

Data Link Layer is divided into 2 sub-layers:

1. Logic Link Control (LLC) or Data Link Control (DLC) Sublayer
2. MAC Sublayer

LLC layer takes the network protocol data and adds control information to help deliver the packet to the destination (Flow control)

MAC sublayer is implemented by hardware by Computer NIC, is primary responsible for:

1. Data encapsulation - Frame assembly before transmission and disassembly upon reception
2. Media access control

Primary usecases of MAC sublayer are:

1. Framing
2. Physical Addressing or [[MAC Address|MAC Addressing]]
3. Error Control

| Service             | Sublayer   |
| ------------------- | ---------- |
| Flow Control        | LLC or DLC |
| Framing             | MAC        |
| Physical Addressing | MAC        |
| Error Control       | MAC        |
| Access Control      | MAC        |

# Related Notes

1. [[Computer Network]]
2. [[Data Link Layer]]
# References

1. 