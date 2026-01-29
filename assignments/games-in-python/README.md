

# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic Hangman game in Python. You'll practice string manipulation, loops, conditionals, and random selection by creating a word-guessing game where players try to reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️ Create the Hangman Game

#### Description
Write a Python program that implements the Hangman game. The game should randomly select a word from a predefined list, accept letter guesses from the player, and display the current progress. The game ends when the player either guesses the word or runs out of attempts.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Accept letter guesses from the user (one letter at a time)
- Display the current progress using underscores for unguessed letters (e.g., _ a _ _ m a n)
- Track and display the number of incorrect guesses remaining
- End the game when the word is fully guessed or attempts are exhausted
- Display a win message if the player guesses the word, or a lose message if they run out of attempts

Example:
```
Word: _ _ _ _ _ _ _
Guesses left: 6
Guess a letter: a
Word: _ a _ _ _ a _
Guesses left: 6
Guess a letter: e
Word: _ a _ _ _ a _
Guesses left: 5
...etc...
```
