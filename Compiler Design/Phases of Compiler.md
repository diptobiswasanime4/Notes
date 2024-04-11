Created: April-03-2024

1. [[Lexical Analysis]]
2. [[Syntax Analysis]]
3. [[Semantic Analysis]]
4. [[Intermediate Code Generation]]
5. [[Code optimization]]
6. [[Target code generation]]

Phase-wise 1, 2, 3 are called [[Analysis Phase]], while 4, 5, 6 are called [[Synthesis Phase]]

From Software perspective 1, 2, 3, 4 are called Front-end, while 5, 6 are called Back-end

Apart from these 6 phases, there are 2 more phases:

1. [[Symbol Table Manager]]
2. [[Error Handler]]

Info gathered from [[Analysis Phase]] is stored in the [[Symbol Table Manager]], and used by the [[Synthesis Phase]]

Error generated in any of the 6 phases is handled by the [[Error Handler]]

# Related Notes

1. [[Compiler Design]]
2. [[Compiler]]
# References

1. 