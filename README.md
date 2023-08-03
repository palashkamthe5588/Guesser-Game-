# Guesser-Game-
Here's how the code works:

Guesser Class: Represents the Guesser, who guesses a number.

guessNumber() method: Takes input from the user (the Guesser) using a Scanner to guess a number. Returns the guessed number.
Player Class: Represents a Player, who also guesses a number.

guessNumber() method: Takes input from the user (a player) using a Scanner to guess a number. Returns the guessed number.
Umpire Class: Manages the game by collecting guesses and determining the winner(s).

collectNumFromGuesser() method: Creates an instance of the Guesser class and collects the guess.
collectNumFromPlayer() method: Creates instances of three Players and collects their guesses.
compare() method: Compares the Guesser's number with the players' numbers to determine the winner(s) and prints the result.
Launchgame Class (Main): Creates an instance of the Umpire class, collects guesses from the Guesser and Players, and then compares the guesses to determine the winner(s).

# Number Guessing Game

This is a simple number guessing game implemented in Java. The game involves a Guesser and three Players, with an Umpire to determine the winner(s).

## How to Play

1. Run the `Launchgame` class to start the game.
2. The Guesser will guess a number.
3. Three Players will guess numbers.
4. The Umpire will compare the guesses and announce the winner(s).

## Classes

### Guesser

- Represents the Guesser who guesses a number.
- Method: `guessNumber()`
  - Takes input from the Guesser using a Scanner.
  - Returns the guessed number.

### Player

- Represents a Player who guesses a number.
- Method: `guessNumber()`
  - Takes input from a Player using a Scanner.
  - Returns the guessed number.

### Umpire

- Manages the game by collecting guesses and determining the winner(s).
- Method: `collectNumFromGuesser()`
  - Creates an instance of the Guesser class and collects the guess.
- Method: `collectNumFromPlayer()`
  - Creates instances of three Players and collects their guesses.
- Method: `compare()`
  - Compares the Guesser's number with the players' numbers to determine the winner(s).
  - Prints the result.

### Launchgame (Main)

- Creates an instance of the Umpire class.
- Collects guesses from the Guesser and Players.
- Compares the guesses to determine the winner(s).
