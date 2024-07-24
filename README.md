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
https://github.com/kiirty/codealpha_tasks/blob/main/Sudoko%20Solver%20TASK-1

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
https://github.com/kiirty/codealpha_tasks/blob/main/CGPA%20Calculator%20%20TASK-2
## Demo:
<img width="315" alt="image" src="https://github.com/user-attachments/assets/92c24124-d918-445e-b828-44d255e70f26">

## TASK-3 
## Overview: 
This C++ program simulates basic banking operations through functions for account setup, deposits, withdrawals, and displaying account details. It uses input/output operations to interact with users, allowing them to enter account information and transaction amounts. Condition checking ensures withdrawals do not exceed the available balance, and simple data management stores and updates account details. The program features a menu-driven interface, enabling users to select different banking operations. Overall, it demonstrates fundamental programming concepts in C++, such as function definition, data handling, and user interaction, providing a functional model of core banking activities.

## Technology Used:
1. Programming Language:
C++: The core language used for writing the banking system, chosen for its performance, object-oriented features, and extensive standard library.
2. Development Environment:
Integrated Development Environment (IDE): IDEs like Visual Studio, Code::Blocks, or CLion can be used for writing, debugging, and compiling C++ code.
Text Editors: Lightweight editors like Sublime Text, Visual Studio Code, or Notepad++ for writing code.
3. Compiler:
GNU Compiler Collection (GCC): Commonly used for compiling C++ code on various platforms.
Microsoft Visual C++ Compiler: Used with Visual Studio on Windows.
Clang: Another popular C++ compiler, known for its fast compilation and excellent diagnostics.
4. Libraries:
Standard Template Library (STL): Provides a collection of algorithms, containers, and iterators, essential for efficient data handling.
Boost: A set of libraries that enhances C++ functionality, useful for advanced features not covered by the STL.

## Key Features:
1)  Account Creation and Initial Balance Setup

- Function: 'opbal'
- Prompts the user to enter the account holder's name, account number, account type, and initial balance.
Stores this information in the respective member variables.
2) Deposit Money
- Function: deposit
- Prompts the user to enter a deposit amount.
- Adds the deposit amount to the current balance.
- Displays the new balance after the deposit.
3) Withdraw Money
- Function: withdraw
- Checks if the withdrawal amount is less than or equal to the current balance.
- If sufficient funds are available, subtracts the withdrawal amount from the balance.
- Displays the new balance after the withdrawal.
- If insufficient funds, displays an error message.
4) Display Account Details
- Function: display
- Displays the account holder's name, account number, account type, and current balance in a formatted manner.
5)Menu-Driven User Interface
- Main Function: main
- Provides a menu for the user to select different operations:
- Assign Initial Value (create account and set initial balance)
- Deposit money
- Withdraw money
- Display all account details
- Exit the program
- Uses a do-while loop to repeatedly show the menu until the user chooses to exit.
- Switch-case structure to handle user choices and call the corresponding functions.
- 
 ## Installation:
 view-source:https://github.com/kiirty/codealpha_tasks/blob/main/Banking%20System%20TASK-3

 ## Demo:
 ![Screenshot 2024-07-24 083412](https://github.com/user-attachments/assets/41dd4325-27f0-4eca-b17a-b2f070c5bc70)
![Screenshot 2024-07-24 083430](https://github.com/user-attachments/assets/4e47fb08-11c1-47fe-a62b-e9fae1755792)
![Screenshot 2024-07-24 083440](https://github.com/user-attachments/assets/bf03bd9f-ac3a-4be9-b5ca-1cc83e130dcc)



