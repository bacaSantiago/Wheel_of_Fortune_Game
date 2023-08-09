# Wheel of Fortune Python Game

Welcome to the Wheel of Fortune Python game! This text-based game simulates the classic TV show "Wheel of Fortune," where players guess letters and phrases to win cash and prizes. Below, you'll find an overview of how the game works and details about the provided code.

## Game Overview

- Players: There are human and computer players participating in the game. Each player starts with no money and no prizes.

- Objective: The goal is to guess a phrase within a specific category. Players take turns spinning the wheel, guessing letters, and attempting to solve the phrase.

- Wheel Spins: When a player's turn begins, they spin the wheel, which determines the prize for their turn. The wheel can land on cash amounts, "lose a turn," or "bankrupt."

- Guessing Letters: Players can guess letters to uncover the hidden phrase. Correct guesses earn cash based on the number of times the guessed letter appears in the phrase.

- Guessing the Phrase: Players can also guess the entire phrase. If correct, they win the game. Incorrect guesses result in the next player's turn.

- Pass: Players can choose to pass their turn if they are unsure about guessing a letter or the phrase.

## Code Explanation

The provided code implements the Wheel of Fortune game. Here's a brief explanation of the main components:

1. **Player Classes**: The code defines two player classes: `WOFPlayer`, `WOFHumanPlayer`, and `WOFComputerPlayer`. These classes store player information such as name, prize money, and prizes won.

2. **Game Logic**: The game logic is managed by various functions like `getMove`, `spinWheel`, `getRandomCategoryAndPhrase`, and more.

3. **Game Play**: Players take turns spinning the wheel, guessing letters, and solving the phrase. The game continues until a player correctly guesses the entire phrase.

4. **Phrase and Wheel Data**: The game uses external data files, "phrases.json" and "wheel.json," to provide categories, phrases to guess, and wheel spin options.

## How to Play

1. Run the provided code in a Python environment.
2. Follow the prompts to enter the number of human and computer players and their names.
3. Choose the difficulty level for computer players (if applicable).
4. Players take turns spinning the wheel, guessing letters, and solving the phrase.
5. The game continues until a player wins by guessing the complete phrase.

## Data Files

1. "phrases.json": Contains phrases for various categories.
2. "wheel.json": Defines the wheel's options, including cash amounts, "lose a turn," and "bankrupt."

## Customization

Feel free to modify the provided code, add more phrases, change the wheel's options, or enhance the gameplay to match your preferences.

Enjoy playing the Wheel of Fortune Python game! Feel the excitement of spinning the wheel, making guesses, and competing against friends or computer opponents to solve phrases and win prizes.