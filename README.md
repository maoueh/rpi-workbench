# Details

This contains some code I made toying with my Raspberry PI. Feel free
borrowing anything from this.

## Building

Building is done through Eclipse and the configured toolchain (i.e. compiler
and stuff like that) is a cross-compiler running on Windows 7 with [MSYS2](http://sourceforge.net/projects/msys2/)
as a dependency.

The cross-compiler compiles code targeting architecture ARMv6 using
hardware float support.

Contact if you want a pre-compiled package installable in [MSYS2](http://sourceforge.net/projects/msys2/).
I plan on making this cross-compiler toolchain available as a package to all 
[MSYS2](http://sourceforge.net/projects/msys2/) but I have not taken the time
right now.

## Hardware Wiring

When possible, I tried giving some schematic of the electrical setup needed
to make the code work correctly. This is probably useful for myself when I 
will want to come back to Raspberry PI development.
