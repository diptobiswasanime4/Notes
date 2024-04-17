Created: April-17-2024

- Provides unidirectional Data transmission with [[Flow Control]] facilities but without Error control
- Here sender sends one [[Packet]], receives ACK then sends another Packet
## Problems

1. Lost Data - If data is lost in between, the receiver will never send back the ACK and the sender will keep on waiting for an unbelievably long period of time
2. Lost ACK - Similar issue as 1
3. Delayed Data/ ACK - Delayed ACK might be considered by the sender as the ACK of some other data packet
# Related Notes

1. [[Computer Network]]
2. [[Packet]]
# References

1. 