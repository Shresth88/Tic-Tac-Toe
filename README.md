# Programming Assignment : 2-player-game

## Overview

This assignment involves creating a two-player Tic-Tac-Toe game. The game should allow players to take turns, display the current game status, and provide an option to reset the game at any time.

## Game Description

Tic-Tac-Toe is a classic game played on a 3x3 grid by two players who alternately place their marks (X or O) in empty squares. The objective is to be the first to form a horizontal, vertical, or diagonal line with three of one's own marks.

## Reference Screenshots

Initial Screen:
![Initial Screen](/public/initial-screen.png)

Player X's turn:
![Player X's turn](/public/after-player-x-selected.png)

Player O's turn:
![Player O's turn](/public/player-o-selected.png)

After the game is won:
![Player X wins](/public/player-x-wins.png)

After the game is drawn:
![Draw](/public/draw.png)

## Requirements

- **Turn-Based Play**: Players should be able to take turns placing their marks (X or O) on the board.
- **Win Detection**: The game should detect when a player has won by forming a horizontal, vertical, or diagonal line with three of their marks.
  - After the win, the game should stop and display the winner.
  - Only resetting, will aloow the game to be started
- **Game Status Display**: Display the current game status at the top of the interface, indicating whose turn it is, announcing the winner, or declaring a draw if applicable.
- **Reset Functionality**: Include a "Reset" button that allows players to restart the game at any time.

## Development Setup

1. **Fork the Repository**: Fork this repository to your own GitHub account.
2. **Clone the Repository**: Clone your forked repository to your local machine.
   ```
   git clone https://github.com/your-username/2-player-game.git
   cd 2-player-game
   ```
3. **Install Dependencies**: Install the required dependencies.
   ```
   npm install
   ```
4. **Start the Development Server**: Run the local development server.
   ```
   npm run dev
   ```
   This will start the server and open the application in your default browser.

## Submission Guidelines

Please submit your completed project by:

1. Pushing your changes to the forked repository in GitHub Codespaces
2. Including comments in your code explaining your implementation details
3. Ensuring your code runs without errors and produces a functional Tic-Tac-Toe game
4. Submitting the link to your repository
5. Add your email-id, name and roll number in the README.md in the below format
   - Name: <your name>
   - Email-id: <your email-id>
   - Roll Number: <your roll number>

## Important Notes

- Ensure your code is clean and well-documented.
- Test your game thoroughly to ensure all functionalities work as expected.
- Make sure your code is free of syntax errors and runs without issues.
- Use the provided guidelines and requirements to complete the assignment.
