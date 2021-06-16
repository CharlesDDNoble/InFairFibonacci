# InFairFibonacci
A fibonacci number generator for SPL (Shakespeare Programming Language). SPL is 
an esoteric programming language by Jon Åslund and Karl Hasselström that attempts to 
recreate the writing style of Shakespeare in its source code. See 
[this](https://en.wikipedia.org/wiki/Shakespeare_Programming_Language) wikipedia page for more details.

## Dependency
[Shakespearelang](https://github.com/zmbc/shakespearelang) is a pretty nifty project for compiling, running, 
and debugging SPL, check it out. It uses python to parse and run SPL, so any machine that has python installed 
*should* be able to run it! Other SPL compilers/interpreters are available...

## Running the program
The program can be run using Shakespearelang with the following command:
```
  shakespeare run infairfibonacci.spl
```
It expects 1 integer input n, and will output the nth fibonacci number.

```
Desktop>shakespeare run infairfibonacci.spl
>6
8
```

Pretty simple, it's the code that the fun part! Check out the source!
