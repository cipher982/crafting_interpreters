# Challenges
1. The lexical grammars of Python and Haskell are not regular. What does that mean, and why aren’t they?

- A regular grammar is a grammar that can be represented by a regular expression. A regular expression is a pattern that describes a set of strings. So the answer is that Python and Haskell are not regular grammars because they cannot be represented by a regular expression.

2. Aside from separating tokens—distinguishing print foo from printfoo—spaces aren’t used for much in most languages. However, in a couple of dark corners, a space does affect how code is parsed in CoffeeScript, Ruby, and the C preprocessor. Where and what effect does it have in each of those languages?

- In CoffeeScript, spaces are used to separate tokens. In Ruby, spaces are used to separate tokens and to indicate the end of a statement. In the C preprocessor, spaces are used to separate tokens and to indicate the end of a statement.

3. Our scanner here, like most, discards comments and whitespace since those aren’t needed by the parser. Why might you want to write a scanner that does not discard those? What would it be useful for?

- If you want AI to parse your code.

4. Add support to Lox’s scanner for C-style /* ... */ block comments. Make sure to handle newlines in them. Consider allowing them to nest. Is adding support for nesting more work than you expected? Why?

- idk.