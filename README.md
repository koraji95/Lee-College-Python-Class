# Lee-College-Python-Class

This readme explains how the Sudoku puzzle works:

You are given an empty board, and it reads X_RC values which correspond to the value at the rth row, cth column starting with 0- index.
after each move, finds next row, then returns row, it checks each move to see that its a valid guess. and if it is, places it at the spot on the board, then we call our solver, if not valid or if nothing gets returned true, we backtrack and try a new number, if no new numbers then the puzzle becomes unsolveable
