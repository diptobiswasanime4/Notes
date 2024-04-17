Created: April-17-2024

**Bit Stuffing** views frame as a collection of bits

In HDLC we have a problem,

the beginning and the ending sequence is 01111110

But what if there is 01111110 in between

The receiver may mistake it as the end of the Frame

To solve this issue we have *Bit Stuffing*

Sender will simply add a 0 after 5 1s in between and the receiver will remove it

# Related Notes

1. [[Computer Network]]
2. [[High-Level Data Link Control (HDLC)]]
# References

1. 