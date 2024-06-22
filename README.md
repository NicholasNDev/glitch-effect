# glitch-effect
git repo: https://github.com/mikolajArchUser/glitch-effect
simple command line glitch effect based on ncurses

## Dependencieis
You will need ncurses library to compile this program. 
You can install ncurses using your package manager as `ncurses-dev` or `libncurses-dev`.

## Compiling and running
<!--
First compile the c++ script with g++:

```
g++ -o glitch glitch.cpp -lncurses
```
-->

To compile project use the makefile provided in the repo:

```
make
```

You can run your executable with `./glitch`.
For options run `./glitch --help`.

## Where to start?

You can move or copy your executable to `/usr/bin` so you can run it whenever you want.
You need to specify a text file to display, you can start with files provided in my repo.
