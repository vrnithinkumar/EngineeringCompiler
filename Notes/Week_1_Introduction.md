# Introduction 
- **Compiler**

    Convert the whole program to compiled code in a single compilation. Then it can be used to compile it.
- **Interpreters**

    Real time interpreting based on the input and execute current input based on the context created by previous inputs.

### Structure of a compiler
1. Lexical analysis : Identify and divide code into valid tokens.

![Alt text](Docs/Lexing.png?raw=true "Syntax Tree")

2. Parsing : Identify and parse the structure of the code.

![Alt text](Docs/SyntaxTree.png?raw=true "Syntax Tree")

3. Semantic analysis : To catch inconsistent usages. To avoid ambiguous structure by following the rules. Type matching.

4. Optimization : To minimize the usage of resources without actually affecting the output.

5. Code Generation : Translating to low level assembly language to be executed by the computer.
