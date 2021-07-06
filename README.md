# quickGDB

quickGDB allows a quicker startup debugging time (or a more user-friendly tool for gdb) for debugging C and C++ files with gdb. If you want ``layout src`` and ``break main`` set up automatically, then this is the file you may need. 

Steps (For Linux):

1. Download the file quickGDB.txt and rename it to .gdbinit in your home directory.
2. This only works if the binary executable is named "a.out". Make sure not to use the -o flag when you're compiling with gcc (You can eventually rename the bianry if you managed to finalize your C/C++ program).

That should be it.

Note: GDB does not *run* automatically, the only thing you can do once you start gdb is to type ``r``. You don't need to retype the same commands like ``break main`` and ``layout src`` over and over again anymore.
