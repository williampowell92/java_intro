# Interpreted languages

### Overview

Interpreted languages are not directly executed by the target machine, but instead read and executed by another program, which is normally written in the native language of the machine.

### Advantages

- Easier to implement.
- No need to run a compilation stage, can execute code as and when.
- Can be more convenient for dynamic languages.

# Compiled languages

### Overview

A compiled language is one where the program, one compiled, is expressed in the instructions of the target machine, so functions written in the language are directly translated into the target machines language for execution.

### Advantages

- Faster performance by directly using the native code of the target machine.
- Able to apply powerful optimisations during the compile stage.

# Comparison

Usually an interpreted language is chosen when their are restrictions on the development times of the program and it may have to be edited at a later time. You trade speed of development for execution costs. Often compiled and interpreted languages will both be used in a project, in different parts. If the code will have to be rerun often it may be better to use a compiled language, whilst if the code has to be changed a lot an interpreted language may be better.
