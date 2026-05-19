# 📘 Assignment: Games in Python

## 🎯 Objective

Build a text-based Hangman game to practice core Python skills such as loops, conditionals, string handling, and basic game logic.

## 📝 Tasks

### 🛠️ Build the Core Hangman Loop

#### Description
Create the main game flow for Hangman. The player should guess one letter at a time to uncover a hidden word.

#### Requirements
Completed program should:

- Store a list of possible words and choose one at random.
- Display the hidden word using underscores for unguessed letters.
- Ask the player to enter a single-letter guess each turn.
- Reveal correct letters in all matching positions.
- Continue until the player guesses the word or runs out of attempts.

### 🛠️ Track Guesses and End Conditions

#### Description
Improve your game by tracking incorrect guesses, preventing repeated guesses, and showing clear game results.

#### Requirements
Completed program should:

- Track and display how many incorrect guesses remain.
- Keep a record of guessed letters and ignore duplicates with a friendly message.
- Validate input so only one alphabetical character is accepted.
- Show a win message when the full word is guessed.
- Show a lose message with the correct word when attempts reach zero.
