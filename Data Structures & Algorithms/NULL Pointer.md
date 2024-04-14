Created: April-13-2024

A NULL Pointer is a [[Pointer|pointer]] that does not point to any memory location

It represents an invalid memory location

The value of NULL is 0 but this is not the same as integer 0

Size of NULL pointer depends upon the platform, and is similar to the size of regular pointers

When a NULL value is assigned to a pointer the pointer becomes a NULL pointer

```
int main () {
	int *ptr = NULL;
	return 0;
}
```
## Uses

1. Used to initialize a pointer when it isn't assigned any valid memory address yet
2. Useful for handling errors when using malloc function

# Related Notes

1. [[Data Structures & Algorithms]]
2. [[Data Structure]]
# References

1. 