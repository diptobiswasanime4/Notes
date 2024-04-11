Created: March-22-2024

Every DFA can be defined using a [[Tuple]] containing 5 values:

Q = Set of all states
$\sum$ = Inputs
$\large q_o$ = Initial State
F = Set of final states
$\large \delta$ = Transition function from Q x $\sum$ $\longrightarrow$ Q

![[DFA excal.excalidraw]]

Here,

Q = { $\large q_0, q_1, q_2, q_3, q_4$ }
$\sum$ = { 0, 1 }
$q_o$ = $q_o$
F = { $q_3, q_4$ }
$\large \delta$ = Q x $\sum$ $\longrightarrow$ Q

| $\large \delta$ | 0            | 1            |
| --------------- | ------------ | ------------ |
| $\large q_0$    | $\large q_1$ | $\large q_2$ |
| $\large q_1$    | $\large q_3$ | $\large q_2$ |
| $\large q_2$    | $\large q_1$ | $\large q_4$ |
| $\large q_3$    | $\large q_3$ | $\large q_2$ |
| $\large q_4$    | $\large q_1$ | $\large q_4$ |

When a String reaches a state from where there is no possibility of reaching a final state, it is called **Trap State**

While analyzing a DFA if we don't find which state some of the inputs should go, we can create a **Dead State**

If we resolve a problem that satisfies the opposite of our requirement, we can Flip the states, final states to non-final states, and non-final states to final states to meet our requirements.

# Related Notes

1. [[Theory of Computation]]
2. [[DFA vs NFA]]
# References

1. 