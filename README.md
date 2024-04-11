Tic-Tac-Toe Game
This repository contains the source code for a web-based implementation of the classic Tic-Tac-Toe game using React.js. The game allows two players to take turns playing, with the objective of aligning three symbols (either "X" or "O") in a row, column, or diagonal on the game board.

Features
Player Name Editing: Players can edit their names using the provided interface.
Game Play: Players take turns selecting squares on the game board to place their symbols.
Game Over: The game detects and displays a winner when three identical symbols align in a row, column, or diagonal.
Rematch: Players can restart the game and play again.
Draw Detection: If the board is full and there is no winner, the game is a draw.
Component
The application is composed of several React components:

Player: Allows players to edit their names and displays their active status.
GameBoard: Renders the game board and handles square selection.
GameOver: Displays the game over screen with the winner's name or a draw message.
Log: Displays the log of game turns.
App: The main application component that manages the state and coordinates the different components.
