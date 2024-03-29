Created: March-22-2024

There are two kinds of buffers:

1. Unbounded buffer
2. Bounded buffer
## Unbounded Buffer

Places no practical limit on the size of the buffer.

Consumer may have to wait for new items, but producer can always produce new items.
## Bounded Buffer

Assumes a fixed buffer size.

Consumer must wait if the buffer is empty, and producer must wait if the buffer is full.
# Related Notes

1. [[Operating System]]
# References

1. 