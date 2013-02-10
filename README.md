# MinGW for Mac OSX

This is just the normal MinGW tolchain setup to act as a cross compiler (i.e. it runs on OSX but produces MinGW executables that run on Windows)

Currently based on GCC 4.7, but the makefile should be easily adaptable to other versions of MinGW.

## How to use

If you wanted to compile a normal autoconf based lib with this toolchain you would do something like this:

PATH=/path/to/mingwmac/sdk/usr/bin:$PATH ./configure && make