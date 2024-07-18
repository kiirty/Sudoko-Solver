## Overview:
This code solves sudoku puzzles using a backtracking approach. It's written in C++. The code works by systematically trying all possible values for each empty cell in the puzzle. If a value is found that doesn't violate any of the rules of sudoku, it is added to the puzzle. If no such value can be found, the algorithm backtracks and tries a different value. The algorithm continues until a solution is found or it has exhausted all possibilities.

## Technology Used:
- Programming Language:
 1. C++: The core logic of the Sudoku solver is implemented in C++ for efficient computation and control over the solving process.
- Algorithm:
 1. Backtracking: A recursive backtracking algorithm is used to explore possible solutions by trying different numbers in empty cells and backtracking when a constraint is violated.
- Development Tools:
 1. Compiler: A C++ compiler (e.g., g++, clang++) is used to compile the code.
2. Integrated Development Environment (IDE): IDEs like Visual Studio, Qt Creator, or Code::Blocks can be used for efficient development and debugging.
## Grid Initialization: 
The Sudoku grid is initialized with a given puzzle. You can replace the numbers in the grid variable with any Sudoku puzzle you want to solve.
## Helper Functions:
- isPresentInCol, isPresentInRow, and isPresentInBox check whether a number is already present in a specific column, row, or 3x3 sub-grid, respectively.
- isValidPlace checks if it's valid to place a number in a particular cell.
- findEmptyPlace finds an empty cell in the grid.
## Backtracking Algorithm:
- solveSudoku uses a recursive approach to try placing numbers from 1 to 9 in empty cells and recursively solve the rest of the grid. If a placement leads to a solution, it returns true; otherwise, it backtracks and tries the next number.
## Printing the Grid:
- printGrid prints the Sudoku grid in a readable format.
- You can compile this code using a C++ compiler (e.g., g++) and run the executable to see the solved Sudoku puzzle. This implementation can handle puzzles of varying difficulty levels as the backtracking algorithm systematically tries all possibilities until it finds a solution.


## Installation
1. https://github.com/kiirty/Sudoko-Solver/new/main?filename=README.md

## Demo
<img width="161" alt="image" src="https://github.com/user-attachments/assets/b1cea953-dec9-4e09-8174-b4c36808d1e4">
