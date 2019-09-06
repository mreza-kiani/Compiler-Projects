# Atalk Compiler
In these projects, we implemented a compiler for Atalk, which is an actor base language using Java. 
This compiler consists of 4 phases:

1. In [phase 1](https://gitlab.com/CompilerFall96/Phase1.git) the lexer using [Antlr](https://www.antlr.org) and the parser are created
2. In [phase 2](https://gitlab.com/CompilerFall96/Phase2.git) the symbol table is created by processing the program in the first pass, and some semantics are applied
3. In [phase 3](https://gitlab.com/CompilerFall96/Phase3.git) the second pass iterated and all semantics are done including type check.
4. In [phase 4](https://gitlab.com/CompilerFall96/Phase4.git) the MIPS code is generated.