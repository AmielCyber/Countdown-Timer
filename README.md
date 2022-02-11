# <h1 align="center"> Countdown Timer</h1>

## Description
Displays the current time of the system in use in one second increment and sets up an alarm in the shell.  

## Objective
The objective of this project is to work with several threads(manage threads) in a Unix system and get familiar with 
systems programming.

## File Manifest
* **header.h** - Library imports, constant declarations, structure and function declaration for this C program. 
* **input.c** - Validates user input and sets the three timers.
* **threads.c** - Manages the threads and runs a procedure when a particular alarm goes off.
* **debug.c** - Debugger to see if we are getting the correct arguments and alarm time.
* **main.c** - Our program entry point.
* **Countdown Timer Diagrams.pdf** - Digrams of the program design for this project before it was implemented.

## Compile and Running Instructions
1. Enter the command `make` in the Unix terminal from this repository to compile the micro shell program.
2. Run the program by using this command `./mot` or `mot` 
    * Enter three arguments of integer values when running the program: `mot arg1 arg2 arg3`
        * `arg1` The time in seconds the program will runs.
            * Default of 25 seconds if no arguments are passed
        * `args2` A 1 or 60 second value in which the program will print the system's time.
            * Default of 1 second if no arguments are passed
        * `args3` The countdown timer where an alarm will run in the shell at args3 seconds.
            * Default of 17 seconds if no arguments are passed

3. Enter the command `make clean` in the Unix terminal to remove the executable and any other generated files 
when you are done with the program.

## Extra Features
Followed good practice in .c, .h, and makefile files.

## Known Bugs
None known.

## Authors
* [Obada Algha](https://github.com/obadaalagha)
* [Amiel Nava](https://github.com/AmielCyber)
