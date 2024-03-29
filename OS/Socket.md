Created: March-22-2024

 - Socket is defined as an endpoint for communication
 - A pair of processes communicating over a [[Computer Network]] employ a pair of sockets, one for each process
 - A socket is identified by an [[IP Address]] concatenated with a [[Port Address|Port number]]
 - The server waits for incoming client requests by listening to a specified [[Port]]. Once a request is received, the server accepts a connection from the client to complete the connection.
 - Port numbers < 1024 are assigned to standard processes and hence cannot be assigned to a process
### Communication Between Sockets

- Client process initiates request for a connection, it is assigned a Port by the host (Port number is arbitrary but > 1024)
- Packets travelling between the hosts are delivered to the appropriate process based on the destination port number
# Related Notes

1. [[Operating System]]
# References

1. 