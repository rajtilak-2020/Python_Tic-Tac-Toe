# Tic Tac Toe Game

## Description
A simple, interactive command-line implementation of the classic Tic Tac Toe game, built using Python. This project provides a fun and engaging way to play Tic Tac Toe against a computer opponent with basic AI capabilities.

## Features
- **Player vs Computer Gameplay**: Compete against an AI that makes strategic moves.
- **Interactive Input**: Enter moves via keyboard inputs.
- **Automatic Board Display**: The board updates and displays after every move.
- **Win/Tie Detection**: The game determines winners or ties and displays appropriate messages.

## How to Run
1. Ensure Python is installed on your system.
2. Copy the code into a file named `tic_tac_toe.py`.
3. Open a terminal or command prompt.
4. Run the script using:
   ```bash
   python tic_tac_toe.py
   ```
5. Follow the prompts to play the game.

## How to Play
1. Choose to play the game by typing `Y` or exit by typing `N` when prompted.
2. Enter a position (1-9) to place your move ("X") when it's your turn.
3. The computer will make its move ("O") automatically.
4. Continue until there's a winner or the board is full (resulting in a tie).

## Game Rules
- The board consists of 9 cells numbered 1-9:

  ```
   1 | 2 | 3
  -----------
   4 | 5 | 6
  -----------
   7 | 8 | 9
  ```
- Players take turns placing their marks ("X" for the user and "O" for the computer).
- The first player to align three marks vertically, horizontally, or diagonally wins.
- If the board is full and no player has aligned three marks, the game ends in a tie.

## Technologies Used
- **Python**: The entire game logic is written in Python.
- **Random Module**: Used for AI's strategic and random move selection.

## File Overview
- `tic_tac_toe.py`: The main script that contains the game logic and runs the program.

## Future Enhancements
- Add a graphical user interface (GUI) using libraries like Tkinter or Pygame.
- Implement difficulty levels for the AI.
- Support for Player vs Player mode.

## License
This project is open-source and available under the [MIT License](LICENSE).

---

Enjoy the game and have fun improving your strategy!

