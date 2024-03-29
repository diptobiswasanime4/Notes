Created: March-22-2024

Whether communication is direct or indirect, messages exchanged by communicating processes reside in a temporary queue.

Such queues can be implemented in 3 ways:

1. Zero capacity buffer - Queue has a max length of Zero, thus the link cannot have messages waiting in it. In this case, the sender must block until the recipient receives the message
2. Bounded capacity - The queue has finite length, this at most n messages can reside in it.
3. Unbounded capacity - The queue length is potentially infinite, thus any number of messages can wait in it
# Related Notes

1. [[Operating System]]
# References

1. 