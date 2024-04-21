
# Chess

This is a simple command-line implementation of the classic game of Chess written in Ruby. It allows two players to play against each other in a traditional game of Chess, following the standard rules and conventions.

## Features

- **Traditional Chess Rules**: The game follows the standard rules of Chess, including piece movements, capturing, check, and checkmate.
- **Turn-Based Gameplay**: Players take turns moving their pieces across the board.
- **Pawn Promotion**: When a pawn reaches the opponent's back rank, it can be promoted to any other piece (queen, rook, bishop, or knight).
- **En Passant**: The game supports the en passant rule, allowing pawns to capture opponent pawns that move two squares forward from their starting position.
- **Save and Load Game**: Players can save the game at any point and resume it later.
- **Command-Line Interface**: The game is played through a command-line interface, with prompts and instructions provided for player input.

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/Ismat-Samadov/Chess.git
```

2. Navigate to the project directory:

```bash
cd Chess
```

3. Ensure you have Ruby installed on your machine.

4. Run the game:

```bash
ruby game.rb
```

## How to Play

- Follow the on-screen instructions to make your moves.
- Enter the file and rank of the piece you want to move, followed by the file and rank of the destination square.
- If you need help or want to quit the game, type `help`, `exit`, or `quit` at any time.
- You can also save the game by typing `save`, and load a saved game when starting the program.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.