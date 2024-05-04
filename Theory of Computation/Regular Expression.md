Created: March-22-2024

Important Operators:

1. $\large +$ is Union
2. $\large .$ is Concat
3. $\large *$ is Kleene Closure

Regular Expressions are used for representing certain sets of strings in an Algebraic fashion.

1. Any terminal symbol, including ^ and $\large \phi$ are Regex
2. The Union U of 2 regex is also a regex
3. The Concatenation of 2 regex is also a regex
4. The Closure * of a regex is also a regex
5. The regex over $\sum$ are obtained by recursively applying the above rules 1, 2, 3 & 4 once or more
## Identities of Regex

1. $\large \phi$ + R = R
2. $\large \phi$R + R$\large \phi$ = $\large \phi$
3. $\in$R = R$\in$ = R
4. $\in$* = $\in$ and $\phi$* = $\in$
5. R + R = R
6. R* R* = R*
7. R R* = R* R
8. (R*)* = R*
9. $\in$ + R R* = $\in$ + R* R = R*
10. (PQ)* P = P (QP)*
11. (P + Q)* = (P* Q*)* = (P* + Q*)*
12. (P + Q) R = PR + QR and R (P + Q) = RP + RQ

# Related Notes

1. [[Theory of Computation]]
# References

1. 