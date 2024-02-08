# 15-Puzzle Solver with Weighted A* Search

## Project Details:

- Course: Artificial Intelligence, NYU

## Project Description:

Welcome to our 15-Puzzle Solver project! Here, we implement the weighted A* search algorithm with graph search to solve the 15-puzzle problem. 

### Problem Description:

The 15-puzzle problem is as follows:
- On a 4 x 4 board, there are 15 tiles numbered from 1 to 15 and a blank position.
- A tile can slide into the blank position if it is horizontally or vertically adjacent to the blank position.
- Given a start board configuration and a goal board configuration, the goal is to find a move sequence with a minimum number of moves to reach the goal configuration from the start configuration.

### Algorithm Details:

- We implement the weighted A* search algorithm with graph search.
- The heuristic function h(n) is defined as the sum of chessboard distances of the tiles from their goal positions.
- The value for W is an input parameter in our implementation.
- Graph search does not allow repeated states.

### Input and Output Formats:

- The program reads the value for W, the initial and goal states from a text file.
- The input file contains 11 lines:
    - Line 1: Value for W.
    - Line 2: Blank line.
    - Lines 3 to 6: Tile pattern for the initial state.
    - Line 7: Blank line.
    - Lines 8 to 11: Tile pattern for the goal state.
- W is a floating-point number, while n and m are integers ranging from 0 to 15, representing the blank position (0) and the tile numbers (1-15).
- The program produces an output file containing 15 lines:
    - Lines 1 to 4: Tile pattern for the initial state.
    - Line 5: Blank line.
    - Lines 6 to 9: Tile pattern for the goal state.
    - Line 10: Blank line.
    - Line 11: Value of W from the input file.
    - Line 12: Depth level d of the shallowest goal node found by the search algorithm.
    - Line 13: Total number of nodes N generated in the tree (including the root node).
    - Line 14: Solution sequence represented by A's (movements: L, R, U, D).
    - Line 15: f(n) values of the nodes along the solution path.

## Team:

- Team Members: [Leisha Murthy, Andrew Asseily]
  

##Languages:

- Python
