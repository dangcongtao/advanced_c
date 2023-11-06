# using to compile code file #

# basic 
1. create run file: gcc -o runfile src_file.c
2. ./runfile to run file execute.

> [!NOTE]
> based on docs(C Programming book)
> 3 steps to convert a C program to an execute file.

- **step 1 - Preprocessing:** 
    > make a modified program.
- **step 2 - Compiling:** 
    > the modified program will be translated into machine instructions(`object code`). but it isn't quite ready to run yet.
- **step 3 - Linking:**
    > final step. Linker combine `object code` with any additional code that needed to yeild a complete executable program.
