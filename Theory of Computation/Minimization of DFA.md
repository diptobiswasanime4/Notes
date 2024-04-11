Created: March-22-2024

Minimization of [[Deterministic Finite Automata (DFA)|DFA]] is required to obtain the minimal version of any DFA which consists of the minimum number of possible states.
## Equivalence

Two states A and B are said to be equivalent either if:

1. Both A and B, on getting input X, goes to Final State, $\large \delta$$(A,X) \longrightarrow F$ and $\large \delta$$(B,X) \longrightarrow F$
2. Both A and B, on getting input X, goes to a non-Final State, $\large \delta$$(A,X)$ $\large \nrightarrow$ $F$ and $\large \delta$$(B,X)$ $\large \nrightarrow$ $F$
## Types of Equivalence

If | X | = n, then A and B are said to be n equivalent

This is used to minimize a DFA
## Methods to Minimize DFA

1. Partitioning Method
2. Myhill Nerode Theorem
## Partitioning Method

If 2 rows are giving same result consecutively, you should stop the process.

If a DFA contains an Unreachable State, we can simply remove it.
## Myhill Nerode Theorem (Table Filling Method)

1. Draw a table for all pairs of states (P,Q)
2. Mark all pairs where P $\large \epsilon$ F and Q $\notin$ F
3. If there are any unmarked pairs (P,Q) such that $\large \delta$ (P,X), $\large \delta$ (Q,X) is marked, then mark (P,Q)
4. REPEAT step 4 until no more markings can be done
5. Combine unmarked pairs and make them into a single state

# Related Notes

1. [[Theory of Computation]]
# References

1. 