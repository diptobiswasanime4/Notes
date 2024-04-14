Created: April-14-2024

**Dangling Pointer** is a [[Pointer|pointer]] which points to some non-existing memory location

```
int main () {
	int *ptr = (int*)malloc(sizeof(int));
	
	// Code

	free(ptr);
	return 0;
}
```

Easy Solution to the problem is reinitializing the pointer to NULL

```
int main () {
	int *ptr = (int*)malloc(sizeof(int));
	
	// Code

	free(ptr);
	ptr = NULL; // Solution
	return 0;
}
```

Such kind of issues are avoided in [[Rust]] due to the Ownership model of Memory Management

# Related Notes

1. [[Data Structures & Algorithms]]
2. [[Data Structure]]
# References

1. 