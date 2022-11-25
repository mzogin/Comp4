# Universe (Solar System Simulator)

## Project Description
C++ program that displays the planets of our solar system and simulates their movements


## How to Setup & Run Program

Folder comes with a Makefile for compiling all dependencies into an executable using g++.

In terminal, type 'make' to compile and 'make clean' when you wish to clean your directory

When running the executable(which is called 'NBody'), the program is looking for 3 command line arguments

Pass in the follwing:
1. simulation time(total time window for the whole simulation in ms), 
2. step time (time between each step in ms), 
3. The planets.txt file to read in each planet's data

For example, you can use the following command:

./NBody 157788000.0 25000.0 < planets.txt
