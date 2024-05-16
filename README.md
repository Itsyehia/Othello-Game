# Othello Game

Welcome to the Othello Game repository! This project is a classic implementation of the Othello board game, also known as Reversi. The game is built using Python and features a graphical user interface (GUI) created with Tkinter. The game logic includes an AI opponent implemented using the Minimax algorithm with Alpha-Beta pruning for efficient decision-making.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Game Rules](#game-rules)
- [AI Implementation](#ai-implementation)
- [Contributing](#contributing)


## Features

- **User-friendly GUI:** Intuitive interface using Tkinter for easy interaction.
- **Single-player Mode:** Play against an AI opponent.
- **AI Opponent:** Powered by the Minimax algorithm with Alpha-Beta pruning for optimized performance.
- **Real-time Feedback:** Immediate updates and feedback on valid moves and game status.



## Usage

1. Launch the game by running `python main.py`.
2. The game window will open, displaying the Othello board.
3. Player takes turn by clicking on the board to place his pieces.
4. The game ends when no more valid moves are possible, and the player with the most pieces on the board wins.

## Game Rules

- **Objective:** The goal is to have the majority of your color discs on the board at the end of the game.
- **Gameplay:**
  - Players take turns placing their discs on the board.
  - A move is valid if it outflanks one or more of the opponent's discs.
  - Outflanked discs are flipped to the player's color.
  - The game ends when neither player can make a valid move.

## AI Implementation

The AI opponent in this game uses the Minimax algorithm with Alpha-Beta pruning. Here's a brief overview of the approach:

- **Minimax Algorithm:** A recursive algorithm used for decision-making and game theory. It provides an optimal move for the player assuming that the opponent is also playing optimally.
- **Alpha-Beta Pruning:** An optimization technique for the Minimax algorithm. It reduces the number of nodes evaluated in the search tree by eliminating branches that do not influence the final decision.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.


---
