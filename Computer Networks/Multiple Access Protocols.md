Created: April-17-2024

- If there is no dedicated Link present between sender and receiver then multiple stations can access the channel simultaneously
- Hence *Multiple Access Protocols* are required to decrease collision and avoid crosstalk
## Types

1. Random Access Protocol
	1. [[ALOHA]]
	2. [[Carrier Sense Multiple Access (CSMA)|CSMA]]
	3. CSMA/ CD
	4. CSMA/ CA
2. Controlled Access Protocol
	1. [[Reservation]]
	2. [[Polling]]
	3. [[Token passing]]
3. [[Channelization Protocol]]
	1. FDMA
	2. TDM
	3. CDMA

In **Random Access Protocol** all stations have same priority, any station can send data depending on Medium' state (idle or busy). Hence there is a possibility of Collision.

Below procedure can be followed to avoid Collision:

1. Time of access
2. What to do if medium is busy
3. How to determine success or failure of transmission
4. How to resolve conflict

In **Controlled Access Protocol** the stations consult each other to find which station has the rights to send data. A station cannot send unless authorized by other stations (kind of like [[Democracy]])

**Channelization Protocol** is a multiple-access method in which the available [[Bandwidth]] of a link is shared in time, frequency, or through code, between different stations.


# Related Notes

1. [[Computer Network]]
# References

1. 