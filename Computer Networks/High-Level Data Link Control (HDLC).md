Created: April-17-2024

HDLC is the standardization of Synchronous Data Link Control (SDLC) protocol developed by [[IBM]]

It is a bit-oriented [[Protocol]]

In HDLC beginning and ending sequence is 01111110

The sequence is also transmitted during any times the Link is idle so that the sender and receiver can keep their clocks synchronized

Header has Address and Control Field

Body contains Payload

There is also Cyclic Redundancy Check (CRC) for Error detection

![[HDLC protocol excal.excalidraw]]

We have 3 types of HDLC frames:

1. I-Frame - 1st bit is 0
2. S-Frame - 1st 2-bits is 10
3. U-Frame - 1st 2-bits is 11

# Related Notes

1. [[Computer Network]]
# References

1. 