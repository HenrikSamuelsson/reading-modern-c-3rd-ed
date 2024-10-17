# Exercise - Try Compilation

In this exercise I tried to use a compilation command presented in the book. The computer used to try the command runs Windows and a powershell terminal was used to execute the compilation command.

When being in a folder holding the sample file `getting-started.c` the test turned out as follows:

```powershell
PS > c17 -Wall -o getting-started getting-started.c -lm
c17: The term 'c17' is not recognized as a name of a cmdlet...
Check the spelling of the name...
```

The conclusion is that the command based on using `c17` for compilation does not work on my computer.

But there are other options presented in the book for compilation. The following alternative did work to compile and create an executable:

```powershell
PS > gcc -std=c2x -Wall -lm -o getting-started getting-started.c
PS >
```

There were no warnings, and an runnable executable was produced. I will be going forward using `gcc` when working hands on with content from the book.
