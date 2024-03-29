Created: March-22-2024

## Issues

1. Differences in data representation on the client and server machines. Example - representation of 32-bit integers
2. Whereas local procedure calls fail only under extreme circumstances, RPCs can fail, or be duplicated and executed more than once, as a result of common network errors
3. With standard procedure calls, some form of binding takes place during link, load or execution time so that procedure call's name is replaced by memory address of the procedure call. RPC scheme requires a similar binding of the client and the server port, but neither system has full information about the other because they do not share memory.
## Resolution


# Related Notes

1. [[Operating System]]
# References

1. 