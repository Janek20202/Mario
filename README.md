# uMario_Jakowski
uMario C++/SDL2 Game by Janek Olszak

Author: Janek Olszak

EXE and DLL - Download: http://lukaszjakowski.pl/DL/uMario.zip


It is my first game made in C++.

Visual Studio 2012
SDL Tutorials which I have used:
http://lazyfoo.net/tutorials/SDL/index.php


## Build Pre-requisites

FreeBSD:

    $ pkg install cmake sdl2 sdl2_image sdl2_mixer

OS X (brew):

    $ brew install cmake sdl2 sdl2_image sdl2_mixer

## Building and running

    $ make build run

    # or

    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ ./uMario
