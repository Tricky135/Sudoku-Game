# Sudoku-Game
This is the code for the typical Sudoku game created as a project for the programming paatshala hackathon in Lovely Professional University, Phagwara, Punjab.


FEATURES :-
1. Difficulty Levels: The code provides three different Sudoku puzzles with varying difficulty levels: EASY_PUZZLE, MEDIUM_PUZZLE, and HARD_PUZZLE. These predefined puzzles can be used to test the solver on different levels of complexity.

2. Recursive Backtracking Solver: The core of the Sudoku solver uses a recursive backtracking algorithm to solve the puzzle. It tries different possibilities for each cell until it finds a solution that satisfies all Sudoku rules.

3. Validation of Sudoku Rules: The solver includes functions to validate the Sudoku board according to the rules of Sudoku. It checks that each row, column, and 3x3 subgrid (box) contains no repeated numbers, ensuring that the solution is valid.

4. Interactive Sudoku Board with Editable Cells: The code allows users to interact with a Sudoku board directly on the web page. Each cell in the Sudoku grid is editable (contenteditable="true"), allowing users to input numbers. The keyup event listener restricts the input to valid Sudoku numbers (1-9), ensuring that only single-digit entries are allowed in each cell.

5. Automated Sudoku Solver Integration: The application integrates with a Sudoku solver function (SudokuSolver.solve), which can automatically solve the puzzle. When the "Solve!" button is clicked, the current board state is converted into a string (boardToString()), passed to the solver, and the solution (if valid) is displayed back on the board (stringToBoard()). If the board is invalid or unsolvable, the application alerts the user.


TEAM MEMBERS :- 
1. Debkalpa Das
2. Ashu Rathore 
