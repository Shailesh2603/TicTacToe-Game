# Tic Tac Toe Game (Python)

A simple command-line based Tic Tac Toe game for two players written in Python.

## Features

- Two-player gameplay
- Randomized player selection (optional with `toss()` function)
- Input validation and position checking
- Win condition checking
- Replay option after a game ends

## How to Play

1. Run the program using Python 3:
   ```bash
   python tictactoe.py
   ```

2. Player 1 will be prompted to choose their marker (`X` or `O`). Player 2 is automatically assigned the other marker.

3. Players take turns choosing a position (1–9) on the board:
   ```
   1 | 2 | 3
   -----------
   4 | 5 | 6
   -----------
   7 | 8 | 9
   ```

4. The game will check if the position is valid and available. If not, it will prompt the user again.

5. The game ends when a player wins or the board is full (draw).

6. After each game, users are asked whether they want to play again.

## Code Structure

- `display_board(board)`: Prints the current state of the board.
- `player_input()`: Assigns X/O to players based on Player 1's choice.
- `place_marker(board, marker, position)`: Places a marker at the given position.
- `toss()`: Randomly selects who starts first (function included but not currently used).
- `user_position()`: Gets valid position input from the user.
- `is_postition_available(board, position)`: Checks if the position is available.
- `is_board_full(board)`: Checks for draw condition.
- `iswin(board, player)`: Checks win conditions for a player.
- `is_replay()`: Asks users if they want to replay the game.

## Requirements

- Python 3.x

No external libraries are required.

## Notes

- This is a basic terminal game with no AI.
- Useful as a beginner's project to learn about conditionals, loops, functions, and user input validation in Python.

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
```
