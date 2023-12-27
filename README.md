# c-projects-pli
This is my personal repository for C and C++ projects.

## Code:
- Available upon request (pli373775@gmail.com)

# Command-line chess
## Team
Patrick Li, Iason Mihalopoulos, and Taran Agarwal
## Summary: 
- This file implements a program to conduct terminal-based chess games.
- It takes an optinal argument: The filename of a file. The program will write the state of the game to this file on termination.
- In the event of an error, the program will return -1. Otherwise, it will return 0

## Functions:
- Save and load chess games
- Move pieces around the board
- Implement custom chess pieces with their own movesets
  
# PPM photoshop
## Team
Patrick Li and Iason Mihalopoulos
## Summary: 
This file implements a program to conduct photoshop operations on an image. It takes multiple arguments:
- The input filename (default: image.ppm)
- The output filename (default: photoshopped.ppm)
- The name of the operation (rotate, zoom, swirl, etc.)
- The operation parameters (swirl intensity and location, edge detection threshold, etc.)
## Error handling
In the event of an error, the program will return a specified error code. Otherwise, it will return 0 for a successful operation

# Vending machine
- Program that simulates a terminal-based vending machine.
- The user can buy something with sufficient funds and as long as it's in stock.

# Word search
- Program that solves a word-search problem. 
- The user inputs words in the terminal and the program returns the amount of times each word was found.

# Digraph analyzer
- Finds the number of given digraphs/trigraphs in a given text file.
- The results can be printed in ASCII, reverse ASCII, or in descending count order.
  
# Tree Compare
- Simulate a tree-like structure, where a Tree object can have a list of "sibling" and "kid" trees. 
- User can add and remove sibling and children trees

# Big Integers
- Implemented operations on a data type called UInt256, which is a 256-bit unsigned integer data type. 
- Its internal representation contains an array of 8 uint32_t values
- Addition, multiplication, conversion to hex, etc.

# Word count
- Word count program implemented in C and x86-64 assembly.
- Counts the number of words in a given text file, recording number of occurrences, unique words, etc.
- Functions implemented in both C and assembly

# Cache simulator
- Takes in a list of memory acccesses, and simulates what a cache based on certain parameters would do
- Allows for write-allocate, no-write-allocate, write-through, write-back, etc.
- Keeps track of various statistics (hits, misses, total cycles, etc.)

# Parallel merge sort
- Implementation of merge sort whose computation is parallelized with child processes
- Uses fork/join model of computation
- Example of concurrency with processes

# Chat server
- A chat client program that communicates asynchrously with a server in real-time
- Application that allows for communication over a network (specifically TCP connections)
- Uses concurrency and synchronization primitives to coordinate access to shared data
