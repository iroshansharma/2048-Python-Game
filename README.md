# 2048 Python Game

This is a simple implementation of the popular 2048 game using Python and Tkinter. The objective of the game is to combine numbered tiles to reach the 2048 tile.

## Features

- 4x4 grid gameplay similar to the original 2048 game.
- Arrow keys are used for tile movement.
- Randomly adds new tiles (either 2 or 4) after each move.
- Tracks the player's score.
- Detects game over conditions.

## How to Play

Use the arrow keys to move the tiles:

- **Up Arrow**: Move tiles up.
- **Down Arrow**: Move tiles down.
- **Left Arrow**: Move tiles left.
- **Right Arrow**: Move tiles right.

When two tiles with the same number touch, they merge into one.

The game ends when there are no more possible moves.

## Installation and Setup

### Prerequisites:
- Python 3.x installed on your system.
- Tkinter is included with standard Python installations, so no need to install it separately.

### Running the Game:

1. Clone this repository:
   ```bash
   git clone https://github.com/iroshansharma/2048-Python-Game.git

2. Navigate to the project folder:
   ```bash
   cd 2048-Python-Game
3. Run the game:
   ```bash
   python 2048_game.py

### Code Overview
The game is implemented using the Tkinter library for the GUI, and the random module is used to generate random numbers for tile placement.

### Key Components:
**Game2048**: The main class responsible for handling the game logic, GUI updates, and user input.
**init_grid**(): Initializes the game grid with Tkinter labels.
**add_tile()**: Adds a new tile (2 or 4) at a random empty cell.
**handle_key()**: Detects arrow key inputs and moves the tiles.
**move_tiles()**: Moves and merges tiles based on user input.
**check_game_over()**: Checks if there are no possible moves left.

### Demo
