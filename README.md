# lib<project>

## Static Linking

To use the lib<project> static library, do the following:

1. Copy the lib<project>.a file to your project directory.
2. Copy the lib<project>.h header file to your project directory.
3. In your C source files, include the header file using:

    #include "lib<project>.h"

4. Link against the library file using the -l option in gcc:

    gcc -o your_program your_program.c -L. -l<project>
