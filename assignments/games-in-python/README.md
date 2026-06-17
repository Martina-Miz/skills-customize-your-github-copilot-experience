
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game to practice Python strings, loops, conditionals, and user input while managing game state and feedback.

## 📝 Tasks

### 🛠️ Game Setup

#### Description
Create a Hangman game that chooses a word from a list and prompts the player to guess letters until the word is complete or attempts run out.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list.
- Show the current word progress with blanks for unguessed letters (e.g. `_ a _ _ m a n`).
- Accept single-letter guesses from the player.
- Track and display remaining incorrect guesses.
- End with a win message when the player guesses the word.
- End with a lose message when attempts are exhausted.

### 🛠️ Guess Validation and Feedback

#### Description
Validate player input and give clear feedback about guessed letters, repeated guesses, and remaining attempts.

#### Requirements
Completed program should:

- Reject invalid input such as more than one character or non-letter entries.
- Inform the player when they repeat a guess.
- Reveal correct letters in the displayed word progress.
- Count incorrect guesses separately from correct guesses.
- Provide helpful status updates after each attempt.
