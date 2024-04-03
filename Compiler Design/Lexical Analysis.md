Created: April-03-2024

In this phase the high-level language is taken as an input string, and is then broken into tokens.

Below are the important tokens:

1. Identifier - defined by programmers - variables
2. Separator - brackets
3. Keyword - defined by the language
4. Operator - + - * / %
5. Constant
6. Special character - & $

It can then give the below error messages if found:

1. Exceeding length
2. Unmatched string
3. Illegal character

It also eliminates comments, white space, etc.

The program that does the above, we call it: Lexer, Tokenizer, Scanner, etc.

1. Tokenizer counts ++ -- as 1
2. Tokenizer counts += -= as 1
3. Tokenizer anything counts within "" as 1
4. Tokenizer stops at single "

# Related Notes

1. [[Compiler Design]]
# References

1. 