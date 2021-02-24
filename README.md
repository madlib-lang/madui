# MadUI
## Getting started
You just created a new madlib project, if it's your first project you should read the following.
### Notes on Madlib
Madlib is a general purpose programming language that compiles to Javascript. It means that you need to have [Nodejs](https://nodejs.org/) installed and configured in order to make it work. Madlib can target nodejs or browser, by default it will compile for nodejs.
### How to run it
First, you need to compile the program:
```shell
madlib compile -i src/Main.mad
```
Then, you can run it like this:
```shell
node build/Main.mjs
```
