Created: March-22-2024

Mealy Machine can be defined using a [[Tuple]] containing 6 values:

Q = Finite Set of States
$\sum$ = Finite non-empty set of Input Alphabets
$\large \Delta$ = Set of output alphabets
$\large \delta$ = Transition function: Q x $\small \sum$ $\longrightarrow$ Q
$\large \lambda$ = Output function: Q x $\small \sum$ $\longrightarrow$ $\large \Delta$
$\large q_0$ = Initial State

![[Mealy Machine excal.excalidraw]]

In Mealy Machine,

if Input length = n

Output length = n
## Real-life Example

Traffic-light controller is a good example of Mealy Machine

States:

1. Red light
2. Green light
3. Yellow light
4. Blinking Red light

Inputs:

1. 
# Related Notes

1. [[Theory of Computation]]
# References

1. 