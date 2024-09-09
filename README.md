# Tic-Tac-Toe React Project

## Overview

This is a simple Tic-Tac-Toe game built with React. The game allows two players to take turns, check for winners, and start a new game. It features a game board, player name customization, and game logging.

## Features

- Two-player functionality
- Dynamic player name change
- Game board with selectable squares
- Winner determination and game draw detection
- Game reset functionality
- Game log to view previous moves

## Installation

To get started with this project, clone the repository and install the dependencies:

```bash
git clone <repository-url>
cd <project-directory>
npm install
```

## Components

- **App.js**: Main component that handles the game logic and state.
- **Player.jsx**: Component for displaying and updating player names.
- **GameBoard.jsx**: Component for rendering the game board and handling square selections.
- **Log.jsx**: Component for displaying the game moves log.
- **GameOver.jsx**: Component for showing the game outcome (win or draw) and providing a restart option.

## Game Logic

- **Players**: The game features two players, "Player 1" (X) and "Player 2" (O).
- **Turns**: Players take turns to mark the squares on the board.
- **Winning Combinations**: The game checks for winning combinations after each move.
- **Draw**: The game detects a draw if all squares are filled without a winner.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Contributions are always welcome!
