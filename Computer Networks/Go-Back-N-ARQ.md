Created: April-17-2024

- Uses the concept of Protocol pipelining, hence the sender can send multiple frames before receiving an acknowledgement for the 1st frame
- Frames are number using sequence number
- Number of frames can be sent depending on the sender window size N
- If the ACK of a frame isn't received within an agreed upon time period, *all frames in the current window are re-transmitted*


# Related Notes

1. [[Computer Network]]
# References

1. 