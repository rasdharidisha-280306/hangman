# 🐍 Python Hangman CLI Game

A fully functional, command-line interface (CLI) Hangman game built with Python. This project demonstrates core programming logic, modular file structures, and interactive user experiences.

## 🎮 How to Play
1. The game selects a random word from a predefined list.
2. You have **6 lives** to guess the word, one letter at a time.
3. Every incorrect guess results in losing a life and updates the visual ASCII Hangman art.
4. Guess the word before the man is fully hanged to win!

## 🛠️ Technical Features
* **Modularity:** Game logic is separated from visual assets (`hangman_art.py`) and data (`hangman_words.py`).
* **Input Validation:** The game tracks your previous guesses and notifies you if you repeat a letter, preventing unnecessary life loss.
* **Dynamic UI:** Uses f-strings to provide real-time feedback on lives remaining and current word progress.
* **State Management:** Implements a robust `while` loop to manage game-over conditions for both wins and losses.

## 📂 Project Structure
* `main.py` - The core engine and game loop.
* `hangman_words.py` - A dictionary of potential words for the game.
* `hangman_art.py` - Contains the logo and the ASCII art stages for the hangman.

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/your-repo-name.git](https://github.com/YOUR_USERNAME/your-repo-name.git)
