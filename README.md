# Sudoku Solver
I taught students how to make a sudoku solver using backtracking in my service, KIT.

![180px-Dead-ends-1 svg](https://github.com/Andrewzekid/Sudoku-Solver/assets/79450923/ccb11550-a598-4305-b12c-323a3525364e)

Backtracking is an algorithm where a path is followed until a terminal state is reached (Game is over or solution not found).
When the algorithm reaches an invalid state, it "backtracks", like going back to the last turning point if you are in a maze. 
Eventually with enough iterations, the algorithm will be able to find a solution that passes the game.

## How to run
* The 9x9 sudoku board is represented by the GRID variable. Simply paste your values here from online and the solver will solve them.
  
To run the solver, execute the following block of code below within the jupyter notebook:
```
if solve(grid,0,0):
  for i in range(9):
    for j in range(9):
      print(grid[i][j],end=" ")
    print("\n")
else:
  print("no solution for this sudoku")

```
