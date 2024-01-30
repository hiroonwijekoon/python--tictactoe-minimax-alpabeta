# Tic-Tac-Toe AI Project

This repository contains an implementation of Tic-Tac-Toe with different AI player strategies in Python.

## Player Strategies

### 1. **PlayerL0**

- **Description:** Implements a player using the minimax algorithm with alpha-beta pruning.
- **Usage:** Import the `player_Group4` function and use it to make moves.

### 2. **Player_L1**

- **Description:** Implements a player that selects moves based on predefined patterns.
- **Usage:** Import the `player_L1` function and use it to make moves.

### 3. **Player_L2**

- **Description:** Implements a player similar to `Player_L1` but with additional defense strategies.
- **Usage:** Import the `player_L2` function and use it to make moves.

### 4. **Minimax with Alpha-Beta Pruning**

- **Description:** Contains a general implementation of the minimax algorithm with alpha-beta pruning.
- **Usage:** Import the `minimax_alphabeta` function for use in custom player strategies.

## Testing and Analysis

- **Description:** The `game_control` function runs simulations between different player strategies and provides win ratios.

## Usage

1. Import the desired player function from the corresponding file.
2. Use the imported function to make moves in the Tic-Tac-Toe game.

## Example

```python

# Create an empty Tic-Tac-Toe board
board = [
    [0, 0, 0],
    [0, 0, 0],
    [0, 0, 0]
]

# Make a move using Group4 player
player_Group4(board, 1)

# Make a move using Player_L1
player_L1(board, 2)
```
