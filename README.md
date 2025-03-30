# Tic Tac Toe - A Simple Console Game

## Overview
This project is a C implementation of the classic Tic Tac Toe game. It allows a human player to compete against the computer in a turn-based manner. The computer uses random moves, making the game both engaging and unpredictable. The game is played on a 3x3 grid, and the objective is to align three of your symbols (either horizontally, vertically, or diagonally) before your opponent does.

## Features
- **Player vs Computer Mode**: Play against an AI opponent.
- **Randomized Computer Moves**: The computer selects moves randomly, adding an element of surprise.
- **User-Friendly Interface**: Clear instructions and prompts for a seamless experience.
- **Replay Option**: Players can choose to play multiple rounds.

## How to Play
1. Clone this repository to your local machine.
2. Compile the program using any C compiler (e.g., GCC):
   ```bash
   gcc -o program program.c
   ```
3. Run the executable:
   ```bash
   ./prograam
   ```
4. Follow the on-screen prompts to make your move by entering the row and column numbers (1-3).
5. The game ends when there is a winner or no free spaces left on the board.

## Rules
- The game is played on a 3x3 grid.
- The player is assigned the symbol `O` and the computer is assigned `X`.
- Players take turns placing their symbols on the grid.
- The first to align three symbols horizontally, vertically, or diagonally wins.
- If all spaces are filled and no one wins, the game ends in a tie.

## Code Structure
- **`resetBoard()`**: Resets the board to its initial state.
- **`printBoard()`**: Displays the current state of the board.
- **`checkFreeSpaces()`**: Checks for remaining moves.
- **`playerMove()`**: Handles the player's input and updates the board.
- **`computerMove()`**: Generates random moves for the computer.
- **`checkWinner()`**: Determines the winner by checking rows, columns, and diagonals.
- **`printWinner()`**: Displays the result of the game.

## Sample Gameplay
```
   |   |  
---|---|---
   |   |  
---|---|---
   |   |  
Enter row number (1-3): 1
Enter column number (1-3): 1
 O |   |  
---|---|---
   |   |  
---|---|---
   |   |  
Computer's Move:
 O |   | X
---|---|---
   |   |  
---|---|---
   |   |  
```

## Dependencies
- Standard C library: `stdio.h`, `stdlib.h`, `ctype.h`, `time.h`

## Contributing
Feel free to submit issues or pull requests to improve the project. Contributions are welcome!

## License
This project is licensed under the MIT License. Feel free to use and modify it as per the license terms.

