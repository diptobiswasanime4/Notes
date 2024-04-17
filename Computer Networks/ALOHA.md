Created: April-17-2024

- Initially Designed for WLAN but it is also applicable for shared medium
## Types

1. Pure Aloha
2. Slotted Aloha
## Pure Aloha

- Pure Aloha allows stations to transmit whenever they have data to be sent
- Station sends data and waits for ACK
- If ACK doesn't come within allotted time, Station waits for random amount of back-off time (Tb) and re-sends the data
- Different Stations have different back-off time, hence decreasing the probability of collision
- *Throughput of Pure Aloha is maximized when frames are of uniform length*
- If first few bits of a new frame overlaps with the last few bits of an old frame, both frames will be completely destroyed

![[Pure Aloha excal.excalidraw]]

Vulnerable Time, T = 2 x $\large T_fr$

Throughput = G x $\large e ^ {-2G}$

where G = Number of stations that wish to transmit

Max Throughput = 0.184 for G = 0.5
## Slotted Aloha

- Slotted Aloha was developed to improve the efficiency of Pure Aloha
- Time of shared channel is divided into discrete time intervals called slots
- Sending of data is allowed only at the beginning of these slots
- If a Station misses a time slot, it must wait till the next time slot

![[Slotted Aloha excal.excalidraw]]

Vulnerable Time, T = $\large T_fr$

Throughput = G x $\large e ^ {-G}$

where G = Number of stations that wish to transmit

Max Throughput = 0.368 for G = 1
## Comparison Between Pure & Slotted Aloha

| Pure Aloha                                        | Slotted Aloha                                                 |
| ------------------------------------------------- | ------------------------------------------------------------- |
| Any Station can transmit data at anytime          | Any Station can transmit data at the beginning of any slot    |
|                                                   |                                                               |
| Simplicity in implementation, but collision prone | Complex in implement, but halfs collision, doubles efficiency |

# Related Notes

1. [[Computer Network]]
# References

1. 