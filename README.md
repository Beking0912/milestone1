# Milestone 1

It's for LLVM 17.

## Build & Run

Build:

    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ cd ..

Run:

    $ clang -O0 -g -fpass-plugin=`echo build/skeleton/SkeletonPass.*` fileX.cpp

