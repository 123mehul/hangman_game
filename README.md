# Hangman Game in Python


# Introduction

Welcome to Hangman, a classic word-guessing game implemented in Python! Try to guess the hidden word by suggesting letters. Each incorrect guess costs you a life, and you win if you correctly guess the word before running out of lives.

# Features

- Random Word Selection: Picks a random word from a predefined list using the random module.

- Interactive Gameplay: Allows the player to input guesses and displays the current state of the word with correctly guessed letters revealed.

- Visual Feedback: Uses ASCII art from 'hangman_art.py' to display hangman stages as lives are lost.

- Win/Loss Conditions: Ends the game when the word is guessed correctly or when all lives are lost.

- Input Validation: Checks if the guessed letter has already been guessed and provides feedback accordingly.
