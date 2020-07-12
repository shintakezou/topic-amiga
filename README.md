# Topic: Amiga

Collections of Amiga stuffs I'm not the author of,
and that does not require an Amiga or an Amiga emulator.

See also my [Amiga repository](https://github.com/shintakezou/amiga).


## Compiling

If not stated otherwise, things here compile as simple as

    gcc -o name sourcefile.c

Or something more elaborated like

    for s in *.c; do gcc -c $s ; done
    gcc -o program *.o

So far I haven't used provided Makefile and configure script,
if any.
