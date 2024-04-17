Created: April-17-2024

Principle of CSMA is "sense before transmit" or "listen before talk"

- Carrier is busy means, transmission is taking place
- Carrier is idle, means no transmission is currently taking place
- The possibility of collision still exists because of propagation delay
## Types

1. 1-Persistent CSMA
	1. Before sending the station senses the channel
	2. If it is idle, the station starts sending
	3. If busy, the station senses the transmission continuously
2. p-Persistent CSMA
	1. It applies to slotted channels
	2. When a station is ready, it senses the channel
	3. If it is idle, it transmits with Probability P
	4. It defers until next slot with Probability, Q = 1 - P
3. Non-Persistent CSMA
	1. Before sending the station senses the channel
	2. If no one else is sending, the station begins sending itself
	3. If the channel is already in use the station doesn't continually sense it
	4. It waits for a period of time and repeats the Algorithm
4. O-Persistent CSMA
	1. Each node is assigned a transmission order by a supervisory node

Some modified Protocols:

1. [[CSMA-CD]]
2. [[CSMA-CA]]


# Related Notes

1. [[Computer Network]]
# References

1. 