# Guessing Game

This is a simple command-line number guessing game written in Rust.

## Description

In this game, the computer generates a random number between 1 and 100, and the player tries to guess it. After each guess, the game provides feedback, telling the player if their guess was too high, too low, or correct.

## Features

- Random number generation
- User input handling
- Comparison of user's guess with the secret number
- Continuous gameplay until the correct number is guessed

## How to Play

1. Run the program.
2. You'll see the message "Guess the number".
3. Enter your guess when prompted with "Please input your guess (number)".
4. The program will tell you if your guess is too small, too big, or correct.
5. Keep guessing until you find the correct number.
6. When you guess correctly, you'll see "You win" and the game will end.

## Requirements

- Rust programming language

## How to Run

1. Make sure you have Rust installed on your system.
2. Clone this repository or copy the code into a file named `main.rs`.
3. Open a terminal and navigate to the directory containing `main.rs`.
4. Run the following command: cargo run
5. Follow the on-screen instructions to play the game.

## Dependencies

This game uses the following standard Rust libraries:
- `std::io` for input/output operations
- `rand::Rng` for random number generation
- `std::cmp::Ordering` for comparison operations

Make sure to include these dependencies in your `Cargo.toml` file.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](https://github.com/shricastic/guessing_game/issues) if you want to contribute.

## Author

Shrikrushna Gundre

Enjoy the game!
