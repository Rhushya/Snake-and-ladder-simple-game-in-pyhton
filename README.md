# Snake and Ladder Game

A simple command-line implementation of the classic Snake and Ladder game in Python.


## Description

This project is a Python implementation of the traditional Snake and Ladder game. Players roll a die to move across a 100-square board, encountering snakes that send them backward and ladders that help them advance. The goal is to reach or exceed the 100th square to win the game.

## Features

- Simple command-line interface
- Randomized dice rolls
- Predefined snakes and ladders on the game board
- Single-player mode

## Requirements

- Python 3.x



## How to Play

1. Run the script:
   ```
   python game.py
   ```
2. Follow the on-screen prompts to play the game.
3. Press Enter to roll the die on your turn.
4. The game will automatically move your piece and inform you of any snakes or ladders encountered.
5. Continue playing until you reach or exceed square 100 to win the game.

## Game Rules

- Players start at square 0 and take turns rolling a six-sided die.
- Move forward the number of squares shown on the die.
- If you land on a square with a snake's head, you move down to the square with the snake's tail.
- If you land on a square at the bottom of a ladder, you climb up to the square at the top of the ladder.
- The first player to reach or exceed square 100 wins the game.

## Customization

You can customize the game by modifying the following in the `create_board()` function:

- Change the positions of snakes and ladders
- Add or remove snakes and ladders

To support multiple players, modify the `play_game()` function to handle turns for more than one player.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
