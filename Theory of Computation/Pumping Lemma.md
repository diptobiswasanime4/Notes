Created: April-14-2024

- Pumping Lemma is used to prove that a Language is Not Regular
- Pumping Lemma cannot be used to prove that a Language is Regular

If A is a [[Regular Language]] then A has a Pumping length P such that any String S where | S | >= P may be divided into 3 parts S = xyz such that the following conditions must be true:

1. $\large x y^i z \in A$ for every i >= 0
2. | y | > 0
3. | $\large xy$ | <= P

We prove that a Language is not Regular by contradiction

1. Assume that A is Regular
2. It has a Pumping length P
3. All Strings longer than P can be pumped | S | >= P
4. Find String S in A such that | S | >= P
5. Divide S into xyz
6. Show that $\large x y^i z \notin A$ for some i
7. Consider all ways S can be divided into xyz
8. Show that none of these ways can satisfy all 3 pumping conditions at the same time
9. S cannot be pumped hence Contradiction

# Related Notes

1. [[Theory of Computation]]
# References

1. 