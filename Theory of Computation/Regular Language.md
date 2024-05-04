Created: March-22-2024

A language is considered to be a Regular Language if and only if a [[Finite State Machine (FSM)]] recognizes it.

So not Regular Languages are:

- Not recognized by FSM
- Languages that Require memory

Example - abbcccabbccc... is not a regular language because we have to store the repeating part abbccc

![[Regular language excal.excalidraw]]

Let's say we have Python Programming language, and the alphabet is $\sum$

Now there can be infinite programs written

So how to know if a Program $P_i$ is a Python Program or not

One way is to check $P_i$ against all available Strings. But this is

1. Time consuming
2. Not possible to check for infinite languages

So a better way is to check against the rules of the language whether $P_i$ is part of it or not

This is exactly what a [[Compiler]] does.

This is why [[Theory of Computation]] is a prerequisite for [[Compiler Design]]
## Important

A Regular language has:

1. 1 minimal DFA
2. many minimal NFAs, but no of States in minimal NFAs are same
3. No concept of minimal Regular Expression (RE)

If minimum length of a Lang = n

then,

Number of States in FSM (DFA or NFA) >= n + 1

Also,

Number of States in NFA <= Number of States in DFA

# Related Notes

1. [[Theory of Computation]]
# References

1. 