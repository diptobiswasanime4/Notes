Created: March-22-2024

$\large \in$-NFA is defined with a [[Tuple]] containing 5 values:

Q = Set of all states
$\sum$ = Inputs
$\large q_o$ = Initial State
F = Set of final states
$\large \delta$ = Transition function from $Q$ x $\sum$ x $\large \in$ $\longrightarrow$ $\large 2 ^ Q$

Every state on $\in$ goes to itself, unless mentioned otherwise

![[Epsilon NFA Intro excal.excalidraw]]

Every DFA is NFA, so we can convert *NFA* to *DFA*

Every NFA is epsilon-NFA, so we can convert *epsilon-NFA* to *NFA*

# Related Notes

1. [[Theory of Computation]]
2. [[Deterministic Finite Automata (DFA)]]
3. [[Non-Deterministic Finite Automata (NFA)]]
# References

1. 