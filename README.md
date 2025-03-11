Noughts and Crosses with Alpha-Beta Pruning

Overview

This project implements the classic game "Noughts and Crosses" (Tic-Tac-Toe) using the Minimax algorithm with Alpha-Beta Pruning. The AI intelligently selects the best move using the Minimax strategy, optimizing performance through Alpha-Beta Pruning to reduce unnecessary computations.

Features

Two-player game (Player vs AI)

AI uses Minimax with Alpha-Beta Pruning for optimal decision-making

Detects wins, losses, and draws

Interactive board display

Efficient move selection

Technologies Used

Python

Minimax Algorithm

Alpha-Beta Pruning

How It Works

The board is represented as a 3x3 grid.

The AI (playing as 'X') evaluates possible moves using the Minimax algorithm with Alpha-Beta Pruning.

The player (playing as 'O') manually selects a move.

The game continues until there is a win or a draw.

The program displays the board state and announces the result.

Installation

To run the project, ensure you have Python installed. Clone this repository and execute the script:

# Clone the repository
git clone <repository-link>
cd noughts-crosses-ai

# Run the script
python tic_tac_toe.py

Usage

The AI plays as 'X', and the player plays as 'O'.

The board is displayed in the terminal.

The AI automatically makes a move using the best possible strategy.

Modify the script to take user input for a more interactive experience.

Future Improvements

Implement a graphical user interface (GUI).

Allow player selection of AI difficulty levels.

Enable two-player mode without AI.

License

This project is open-source and free to use. Feel free to contribute!

Author

Anant Singhal
