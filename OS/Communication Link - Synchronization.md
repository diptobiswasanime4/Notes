Created: March-22-2024

Communication between processes takes place through calls to send () and receive () primitives. There are different design options for implementing each primitive.

[[Message Passing System|Message passing]] may be either blocking or non-blocking - also known as synchronous or asynchronous

**Blocking send** is when sending process is blocked until the message is received by the receiving process or by the mailbox

**Non-blocking send** is when the sending process sends the message and resumes operation

**Blocking receive** is when the receiver blocks a message until available

**Non-blocking receive** is when the receiver retrieves either a valid message or a null
# Related Notes

1. [[Operating System]]
# References

1. 