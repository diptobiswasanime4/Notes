Created: March-22-2024

RPCs are used when a process residing in a system wants to connect with another process but in a different system connected by a [[Computer Network]]

*Remote Procedure Call (RPC) is a [[Protocol|protocol]] that one program can use to request a service from a program located in another [[Computer]] in a network without having to understand the network details*

- RPC is similar in may ways to [[Interprocess Communication|IPC]] mechanism
- We must use a message based communication scheme because processes are executing in separate systems, i.e. [[Message Passing System]]
- In contrast to IPC, messages exchanged in RPC communication are well structured and are no longer only [[Packet|packets]] of data
- Message is addressed to an RPC daemon listening to a port on the remote system, and contains an identifier of the function to execute and the parameters to pass to that function
- Function is executed as requested, any output is sent back to the requester in a separate message
- RPC system hides the details that allow comm to take place by providing a stub on the client side
- Typically a separate stub exists for each separate remote procedure
- When client invokes a Remote Procedure, the RPC system calls the appropriate stub, passing it the parameters provided to the remote procedure. Stub locates the [[Port]] on the [[Server]] and marshals the parameters, i.e. involves packaging parameters into a form that can be transmitted over a network
- Similar stub exists in the server side and pass message to the client using the same technique
# Related Notes

1. [[Operating System]]
# References

1. 