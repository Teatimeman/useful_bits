# Initial configuration for the develpment environment

## Install basic programs (for linux)
- Update apt-get list
    + $`sudo apt-get update`
- Install GNU Make
    + $`sudo apt-get install make`
- Install libncurses
    + $`sudo apt-get install libncurses-dev`
- Install tree
    + $`sudo apt-get install tree`

## Install emacs
- Downloa emacs (25.3) from http://mirrors.peers.community/mirrors/gnu/emacs/
- Install emacs
    + $`./configure`
        - For errors (e.g. AppKit), refer to [Link](https://lists.gnu.org/archive/html/bug-gnu-emacs/2016-09/msg00603.html)
    + $`make`
    + $`src/emacs -Q`
    + $`make install`
    + $`make clean`
    + $`make distclean`
