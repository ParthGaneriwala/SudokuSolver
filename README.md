# SudokuSolver
Sudoku Solver using Backtracking in Python

We start with an incomplete Board:
1: Find empty space in the board searching for 0's
2: Attempt to place the digits 1-9 in that space
3: Check if that digit is valid in the current spot based on the current board
  a. If the digit is valid, recursively attempt to fill the board using steps 1-3.
  b. If it is not valid, reset the square you just filled and go back to the previous step.
4: Once the board is full by the definition of this algorithm we have found a solution.
5: Display it.


Code Example Output

0 9 0  | 0 0 0  | 0 6 0
0 4 5  | 6 0 7  | 9 0 0
0 0 0  | 2 8 0  | 0 0 0
- - - - - - - - - - - - - 
6 1 0  | 0 4 0  | 0 0 2
0 0 4  | 0 0 0  | 1 0 0
3 0 0  | 0 9 0  | 0 8 5
- - - - - - - - - - - - - 
0 0 0  | 0 2 8  | 0 0 0
0 0 6  | 4 0 3  | 2 7 0
0 3 0  | 0 0 0  | 0 5 0
___________________

2 9 8  | 5 1 4  | 3 6 7
1 4 5  | 6 3 7  | 9 2 8
7 6 3  | 2 8 9  | 5 1 4
- - - - - - - - - - - - - 
6 1 9  | 8 4 5  | 7 3 2
8 5 4  | 3 7 2  | 1 9 6
3 2 7  | 1 9 6  | 4 8 5
- - - - - - - - - - - - - 
5 7 1  | 9 2 8  | 6 4 3
9 8 6  | 4 5 3  | 2 7 1
4 3 2  | 7 6 1  | 8 5 9

Process finished with exit code 0
