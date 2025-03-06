
# Hangman Game

A simple implementation of the Hangman game in Python. The player has to guess a randomly chosen word by guessing one letter at a time. The player has a limited number of incorrect guesses before losing the game.

## Features

- Random word selection from a predefined list.
- Limited number of attempts (6).
- Displays the word with blanks for unguessed letters.
- Tracks guessed letters and attempts.

## Requirements

- Python 3.x

## How to Run

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/hangman-game.git
Navigate to the project directory:

bash
cd hangman-game
Run the Hangman game:

bash
python hangman.py
Follow the instructions in the terminal to guess letters and try to guess the word before running out of attempts.

Game Rules
You start with 6 incorrect attempts.
Guess letters one at a time.
If the letter is in the word, it will be revealed.
If the letter is incorrect, you lose an attempt.
The game ends when you either guess the word or run out of attempts.
