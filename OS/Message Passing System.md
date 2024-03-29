Created: March-22-2024

Message Passing provides a mechanism to allow processes to communicate and synchronize their actions without sharing the same address space.

Message Passing System is particularly useful in a distributed environment, where the communicating process may reside in different [[Computer|computers]] or connected by a [[Computer Network]]

Message passing facility provides 2 operations:

1. Send message
2. Receive message

Size of the message can again be of 2 types:

1. Fixed size
	1. System-level implementation is straightforward
	2. Makes the task of Programming more difficult
2. Variable size
	1. System-level implementation is complex
	2. Makes the task of Programming simpler

Hence if 2 processes want to communicate, they should be able to send and receive messages among each other.

And this can be done by setting up a [[Communication Link]]

There are several ways how the Link can be logically implemented:

1. Direct or indirect communication
2. Synchronous or asynchronous communication
3. Automatic or explicit buffering
# Related Notes

1. [[Operating System]]
# References

1. 