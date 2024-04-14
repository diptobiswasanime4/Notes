Created: April-13-2024

**Void Pointer** is a [[Pointer|pointer]] that has no associated [[Data Type]]

It can point to any data of any type and can be typecasted to any Data Type

```
int main () {
	int n = 10;
	void *ptr = &n;

	printf("%d", *ptr);
	return 0;
}
```

*malloc* and *calloc* (used to allocate memory at [[Runtime]]) returns a void pointer. Due to this reason, they can allocate memory for any Data Type

# Related Notes

1. [[Data Structures & Algorithms]]
2. [[Data Structure]]
# References

1. 