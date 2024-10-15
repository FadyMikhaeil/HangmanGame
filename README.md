# Hangman Game

## Description
The Hangman Game is a classic word-guessing game where players attempt to guess a hidden word by suggesting letters within a limited number of attempts. This Python implementation uses the `random` library to select words from a predefined list, providing a fun and interactive experience.

## Project Structure
- **`main.py`**: Contains the core game logic, including the word selection, player input, and game state management.
- **`hangman_art.py`**: Features the ASCII art for the game’s logo and various stages of the hangman, which visually represent the player's progress.
- **`hangman_words.py`**: Stores a list of potential words for the game, ensuring variety in gameplay.

## How to Install
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/FadyMikhaeil/HangmanGame.git
   
2. **Navigate to the Project Directory:**
   ```bash
   cd HangmanGame
3. **Ensure Python is Installed:**
   - Make sure you have Python 3 installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

4. **Run the Game:**
   ```bash
   python main.py
   
   ## Gameplay Instructions
- When the game starts, you will see the logo and be prompted to guess a letter.
- You have **6 lives** to guess the correct letters in the word.
- If you guess a letter that is part of the word, its position(s) will be revealed.
- If you guess incorrectly, you will lose a life.
- The game ends when you either correctly guess the word or run out of lives.

  ## Features
- Randomly selected words from a list for diverse gameplay.
- Visual representation of the hangman and player progress.
- User-friendly prompts and feedback throughout the game.

