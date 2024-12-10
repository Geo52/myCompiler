# Intro
- complexity spectrum when it comes to interpreters:
    - brainfuck->tree walker->JIT
- major parts
    - lexer
    - parser
    - AST (abstract syntax tree)
    - internal objext system
    - evaluator
# chapter 1 - lexing
## 1.1 - lexical analysis
- the lexer creates tokens which are fed to the parser that then create the AST
    - source code(monkey) -> lexer -> tokens -> parser -> AST
## 1.2 - defining our tokens