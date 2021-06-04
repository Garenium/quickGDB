# quickGDB

The quickGDB allows a quick startup time for debugging C and C++ files with gdb. If you want ``layout src`` and ``break main`` set up automatically, then this is the file you may need. 

Steps (For Linux):

1. Download the file quickGDB.txt and rename it to .gdbinit in your home directory.

That should be it.

Note: GDB does not *run* automatically, the only thing you can do once you start gdb is to type ``run``. You don't need to retype the same commands like ``break main`` and ``layout src`` over and over again anymore.
