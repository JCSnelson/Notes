Applications Generation:
General purpose software - used for a variety of tasks (e.g. PowerPoint)
Bespoke software - made for specific tasks (e.g. traffic control systems)
Utilities - Used to make sure the computer runs well and manage hardware (e.g. defrag)
Open Source - Can view and edit code, community maintained, often free.
Closed Source - Can't view and edit code, often compiled, company maintained, often paid.
Translators - Translates the programs into machine code in order to be run on the system
High Level Language - Abstracted far from machine code, harder to compile/interpret, more understandable to humans, more features, works regardless of the architecture.
Low Level Language - Close to machine code, specific architecture.
Compiler - Compiles the code into an executable which can be run on specific hardware, not easily reversible and cannot see original code.
Interpreter - Line by line interpretation of code, irrespective of hardware, can see all code when run code crashes upon a runtime error, often slower as source code must be translated each time.
Assembler - one to one relationship, mostly removes comments and resolves symbolic references.


Compilation:
Lexical Analysis - Any comments and whitespace removed, tokenization (split into what each separate 'word' means).
Syntax Analysis - Checks tokens are in the correct order according to the syntax rules of the language.
Abstract Syntax Tree - creates a tree of the program with tokens such as assign and then checks the operation has the children that the operation needs and that no tokens are in the wrong places.
Semantic Analysis - Checking consistent types, undeclared variables and reserved identifier misuse (e.g. redefining print)
Code Generation - Code is a built and an executable file is generated.
Code Optimization - happens throughout the compilation