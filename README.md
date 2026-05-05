# Bulls and Cows Game

This is my second project created for the Engeto Online Python Academy. It is a console-based logic game where the user tries to guess a randomly generated 4-digit number. The goal of this project was to practice writing functions, handling user input, using while loops, and working with standard Python libraries.

## Features

The program simulates the classic Bulls and Cows game with the following mechanics:
* The computer generates a secret 4-digit number with unique digits (it cannot start with a zero).
* The user inputs their guess. The program validates the input to ensure it consists of exactly 4 unique digits, contains only numbers, and does not start with a zero.
* The program evaluates the user's guess and returns hints:
  * Bull: Correct digit in the correct position.
  * Cow: Correct digit in the wrong position.
* The game continues in a loop until the user guesses the exact number (4 bulls).
* The program tracks the total number of guesses and measures the time taken to solve the puzzle. It displays a final performance summary at the end.

## How to Run

No external libraries are required. The script uses only built-in Python modules.

1. Download the script.
2. Run it in your terminal or command prompt:
```bash
bulls_and_cows.py
