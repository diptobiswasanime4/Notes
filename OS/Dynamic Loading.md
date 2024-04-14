Created: April-15-2024

With Dynamic Loading, a routine is not loaded until it is called:

1. All routines are kept in disk in a relocatable load format
2. The main program is loaded into memory and it is executed
3. When a routine needs to call another routine, the calling routine checks whether the other routine has been loaded
4. If not the relocatable Linking loader is called to load the desired routine into memory and to update the program's address tables to reflect the change
5. Then Control is passed to the newly loaded routine

# Related Notes

1. [[Operating System]]
# References

1. 