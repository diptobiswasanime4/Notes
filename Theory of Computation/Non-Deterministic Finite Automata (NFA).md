Created: March-22-2024

NFA is easier to design compared to [[Deterministic Finite Automata (DFA)|DFA]]

It is also represented with a [[Tuple]] containing 5 values:

Q = Set of all states
$\sum$ = Inputs
$\large q_o$ = Initial State
F = Set of final states
$\large \delta$ = Transition function from $Q$ x $\sum$ $\longrightarrow$ $\large 2 ^ Q$

![[NFA excal.excalidraw]]

*If there is any way to run the machine that ends in any set of states out of which at least one state is a final state, then the NFA accepts*

In simpler words, NFA can have multiple ends states, if any one of them is the end state then the NFA accepts a given input.

## Dead Configuration

When a state in NFA has no place to go (i.e. the place is not mentioned) it is called **Dead Configuration**
## Real-life Example

Spell-checker is a good example of NFA

States:

1. Analyzing next correct letter
2. Analyzing final word

Inputs:

1. Writing a letter
2. Deleting a letter
3. Pressing submit

There are many wrong spellings, and there is no need to check them. In can simply be state $\large \phi$

# Related Notes

1. [[Theory of Computation]]
2. [[DFA vs NFA]]
# References

1. 