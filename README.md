## TASK-1 
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


## TASK-2
## Overview:
This CGPA Calculator is a useful tool for students who wish to track their academic progress. It calculates the cumulative grade point average (CGPA) for multiple semesters by accumulating the total grade points and credits earned over the course of all the semesters. The program is written in C++.
## Technology Used:
- Programming Language:
1. C++: The core language used to write the CGPA calculator. It provides the necessary functionality for input/output operations, arithmetic calculations, and control structures.
- Standard Template Library (STL):
iostream: Used for input and output operations, such as reading from the console and displaying results.
iomanip: Used for output formatting, such as setting decimal precision.
- Development Environment:
1. IDE/Text Editor: An Integrated Development Environment (IDE) like Visual Studio, Code::Blocks, CLion, or a text editor like VS Code or Sublime Text can be used to write and edit the C++ code.
2. Compiler: A C++ compiler like GCC (GNU Compiler Collection) or MSVC (Microsoft Visual C++) is needed to compile the code.

## Key Features:
 1. Input Handling:
Accept the number of courses.
For each course, accept the credit hours and grade points.
Validate inputs to ensure they are within acceptable ranges (e.g., positive values for credit hours and valid range for grade points).
 2. Calculation:
Calculate the total grade points by multiplying grade points by credit hours for each course.
Sum the total credit hours.
Compute the CGPA by dividing the total grade points by the total credit hours.
 3. Output:
Display the calculated CGPA with appropriate formatting.
Provide a summary of the inputs, if necessary (e.g., total credits and total grade points).
4. Error Handling:
Handle invalid inputs gracefully by providing clear error messages.
Ensure the program does not crash due to invalid inputs.

## Installation:

