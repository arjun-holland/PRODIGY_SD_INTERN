# PRODIGY_SD_04
# Sudoku Solver
This project is a C++ based Sudoku Solver that uses the backtracking algorithm to solve Sudoku puzzles. The program takes an input grid representing an unsolved Sudoku puzzle and fills in the missing numbers to produce a completed Sudoku grid.
# Rules to Solve Sudoku puzzle
When we want to place a number in a cell, we ensures that:
- The number does not already exist in the same row.
- The number does not already exist in the same column.
- The number does not already exist in the same 3x3 subgrid.
If all three rules are satisfied, the number can be placed in the cell. Otherwise, the placement is invalid, and the we will try a different number or backtrack to the previous step.

# Features
- Solves standard 9x9 Sudoku puzzles
- Uses a backtracking algorithm for efficient solving
- Provides a clear and readable output of the solved Sudoku grid
