Building a VM for Retro can be pretty easy.

# Python

If you have Python, do:

::

    cp vm/complete/retro.py retro
    chmod +x retro

# Ruby

If you have Ruby, do:

::

    cp vm/complete/retro.rb retro
    chmod +x retro

# C

The C implementation can be built easily as well. You'll need GCC and Make:

::

    make

OSX users can get the needed tools as part of Xcode. On Windows I've built this under Cygwin, MinGW, and TinyCC.

(As a side note, if you modify the CC variable in the Makefile, you can also build with clang)

# .NET

For users of .NET, compile either vm/complete/retro.fsx (F#) or vm/complete/retro.cs (C#). These can be compiled with either Mono or Microsoft's .NET implementations. For Mono, try:

::

    gmcs vm/complete/retro.cs


