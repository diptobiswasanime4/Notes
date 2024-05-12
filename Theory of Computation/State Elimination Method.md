Created: May-08-2024

It works for DFA, NFA, $\in$-NFA

To do this, we have to simplify the [[Finite State Machine (FSM)]]

1. Remove any non-reachable state
2. Remove Dead States (Trap states)
3. Remove States from which final State is not reachable
4. Merge final states if possible

Above 4 states can be done in any order

We have the new Finite Automata.

But there are some rules.

1. There should not be incoming edge to the initial State
2. Final state shouldn't have any outgoing edge, if there is create a new Final state with $\in$
3. There should be only 1 Final state, try merging, if not possible create a new Final state with $\in$
4. Eliminate states other than initial and final states in any order.

# Related Notes

1. [[Theory of Computation]]
# References

1. 