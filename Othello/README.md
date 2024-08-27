## Othello

#### Overview

Welcome to the Othello game implemented in Python! This project is a console-based version of the classic board game Othello (also known as Reversi). The game supports two-player mode, where players can either play against each other or against a simple AI.
## Table of Content 

- Features
- Installation
- How to Play
- Game Rules
- Contributing
- License
## Features

- Two-Player Mode: Play Othello with a friend.
- AI Opponent: Play against a simple AI that follows basic strategies.
- Valid Moves Highlighted: The game board shows valid moves for the current player.
- Score Display: The game displays the current score for both players.
- Undo Move: Allows players to undo their last move.
- Interactive Console Interface: Simple and intuitive text-based interface.
## Installation

#### Clone the repository:

git clone https://github.com/kunal-1207/Othello.git

cd othello-game

#### Install dependencies (if any are required):

pip install -r requirements.txt

#### Run the game:

python othello.py

    
## How To Play 

1. Start the game by running python othello.py.
2. Choose whether you want to play against another player or the AI.
3. Players take turns placing their pieces (black or white) on the board.
4. The game will automatically flip the opponent's pieces when a valid move is made.
5. The game ends when no valid moves are left for both players, and the player with the most pieces on the board wins.
## Game Rules 

- #### Objective: The objective of the game is to have the majority of your color pieces on the board at the end of the game.
- #### Setup: The game is played on an 8x8 grid. Each player begins with two pieces of their color placed diagonally in the center of the board.
- #### Turns: Players take turns placing a piece on the board in a way that brackets one or more of the opponent's pieces. All bracketed pieces are flipped to the current player's color.
- #### Valid Moves: A move is valid if it brackets one or more of the opponent's pieces either vertically, horizontally, or diagonally.
- #### Endgame: The game ends when neither player can make a valid move. The player with the most pieces on the board is the winner.
## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.
## How to Contribute 

1. #### Fork the repository.

2. #### Create a new branch with your feature or bug fix:

git checkout -b feature-name

3. #### Commit your changes:

git commit -m "Description of feature or fix"

4. #### Push to the branch:

git push origin feature-name

5. #### Open a pull request on GitHub.
## License

[MIT](https://choosealicense.com/licenses/mit/)


