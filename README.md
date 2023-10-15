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

## Design
- The design is based on a set of interconnected classes
- The chess pieces Pawn, Bishop, Knight, Rook, Queen, King, and Mystery have classes of their own
- Each piece has a legal move shape function and the pawn has a legal capture shape function as well
- The individual piece classes are derived from the Piece base class from which they inherit and override most of their functions
- The Board class contains functions for making and altering the board such as a copy constructor, add_piece and remove_piece as well as an overloaded << operator to print out the board
- The Game class contains most of the functionality of the chess game. The Game() constructor sets up the start of the chess game by adding all of the pieces in their appropriate positions
- Game also contains integral functions such as make_move, in_mate, in_checkmate, in_stalemate, and point_value
- We used the simple point value system: pawn (1), knight (3), bishop (3), rook (5) and queen (9)
- Each player starts the game with maximum possible 39 points and loses the corresponding points whenever a piece of their own is captured.

  
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
