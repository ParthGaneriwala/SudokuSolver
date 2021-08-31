# SudokuSolver
Sudoku Solver using Backtracking in Python

We start with an incomplete Board:
```
1: Find empty space in the board searching for 0's
2: Attempt to place the digits 1-9 in that space
3: Check if that digit is valid in the current spot based on the current board
  a. If the digit is valid, recursively attempt to fill the board using steps 1-3.
  b. If it is not valid, reset the square you just filled and go back to the previous step.
4: Once the board is full by the definition of this algorithm we have found a solution.
5: Display it.
```
