Created: April-14-2024

Self referential structures are structures which contain one or more [[Pointer|pointers]] that points to the structure of the same type

```
struct self {
	int p;
	struct self *ptr;
}
```


# Related Notes

1. [[Data Structures & Algorithms]]
2. [[Data Structure]]
# References

1. 