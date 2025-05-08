# Connect4

A simple Java command-line implementation of the classic Connect Four game.

## Features

- Two-player game with customizable symbols for each player.
- 6-row by 8-column board.
- Input commands for help, changing symbols, restarting, and quitting.
- Detects win, check, and checkmate conditions.
- Input validation and error handling for invalid moves.

## How to Play

1. **Compile the program:**
   ```bash
   javac Connect4.java
   ```

2. **Run the program:**
   ```bash
   java Connect4
   ```

3. **Game Commands:**
   - Enter a column number (0–7) to drop your piece.
   - `h` or `H`: Show help menu.
   - `c` or `C`: Change your symbol.
   - `r` or `R`: Restart the game.
   - `q` or `Q`: Quit the game.

4. **Winning:**  
   The first player to connect four of their symbols in a row, column, or diagonal wins.

## Code Structure

- **Constants:**  
  `HEIGHT` and `WIDTH` define the board size (6x8).
- **Main Logic:**  
  The `main` method starts the game loop via `runOnce()`.
- **Gameplay Methods:**  
  - `printBoard()`: Displays the current board.
  - `printHelpMenu()`: Shows available commands.
  - `changeSymbol()`: Lets players pick a new symbol.
  - `restart()`: Resets the board.
  - `fillBoard()`: Places a piece in the selected column.
  - `isGameOver()`, `check()`, `checkMate()`: Game state checks.

## Notes

- Only modify the sections marked with `TODO` as per your assignment instructions.
- Do not share your code to avoid plagiarism issues.
- For help, contact your course staff as directed in the assignment instructions.

---

