# Guess_number_game.py

A simple, interactive Command Line Interface (CLI) number guessing game built using Python. The program generates a random target number between 1 and 100 and guides the player to the correct answer using real-time feedback.

---

## Project Overview

`Guess_number_game.py` showcases basic Python programming fundamentals, including random number generation, user input processing, conditional branch evaluation, and state tracking via loops.

The game dynamically checks user guesses against a hidden number, tracks the number of attempts made, and provides higher or lower hints to help the player solve the puzzle.

---

## Key Features

- **Random Target Generation:** Uses Python's native `random` module to pick a secret integer between 1 and 100 on every run.
- **Real-Time Feedback:** Instantly informs the player whether their guess is `Too low!` or `Too high!`.
- **Score & Attempt Tracking:** Tally counter tracks the exact number of guesses taken to reach the correct answer.
- **Interactive Control Loop:** Uses a clean `while` loop mechanism that runs continuously until the winning condition is triggered.

---

## How It Works

1. **Initialization:** The script imports `random`, sets `attempts = 0`, and selects a secret integer from 1 to 100.
2. **Input Capture:** Prompts the player to enter a numeric guess in the terminal.
3. **Logic Evaluation:**
   - **Lower than target:** Prompts the user to try a higher number.
   - **Higher than target:** Prompts the user to try a lower number.
   - **Equal to target:** Displays a congratulations message along with the total attempt count and exits the game loop.

---

## Core Concepts Covered

- **Module Importing:** Using Python's built-in `random` module to generate pseudo-random numbers.
- **Variables & Counters:** Initializing and incrementing dynamic values (`attempts += 1`).
- **Control Flow:** Constructing infinite execution loops with `while True` and breaking execution based on dynamic conditions.
- **Conditional Logic:** Employing `if-elif-else` control flow to evaluate dynamic user inputs against target values.
- **Type Casting:** Converting string input to integer values (`int(input())`) for numerical calculations.

---

## Key Takeaways

- Demonstrates how to build an interactive terminal game using standard control structures.
- Shows basic state retention inside loop contexts without needing complex frameworks or classes.
- Serves as an ideal foundational project for understanding game logic loops and condition checking in Python.
