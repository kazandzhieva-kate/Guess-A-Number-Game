# Guess-A-Number-Game
What the title says - trying something new.

<img alt="cover" width="555px" src="https://github.com/user-attachments/assets/5461820d-5e32-478a-a3c6-cd4bc925a22f" />


## Game Description

**Guess A Number** is a simple guessing game where the user is supposed to guess the number that the computer has generated. Said number is between **1 and 100** at first, then which each **level** passed (or number guessed) the range expands by a 100 (100, 200, 300, etc.). The user inserts manually **the number of tries** he wishes to have for the certain round.

The computer will tell the user whether each of his guesses is **lower** or **higher** then the expected number each round. The game also asks the user if they would like to **continue**
 playing after each level passed.

The user may **terminate** the game at any point using the **"End"** command at the terminal.

## Solution
This program is built in Python, using the standard library module **random** to generate unpredictable numbers within a given range. 

The main algorithm is a **loop-based** guessing mechanism: the computer selects a hidden number, and the player has a limited number of attempts to guess it correctly. Each guess is checked against the target number with **conditional statements** to give hints (“too high” or “too low”), and the number of remaining tries decreases after each round. 

The code includes **input validation** (rejecting non-numeric values and handling a manual quit command with "end"), making it easier for user interaction. 

The game logic is encapsulated in the play_game() **function**, which separates gameplay from the main loop that manages levels and difficulty progression.

## Link to the Source Code
[SourceCode](guess_a_number.py)

## Screenshots

Example screenshots for the "Guess a Number" game:
<img alt="image" width="555px" src="https://github.com/user-attachments/assets/c913a6c7-b3e2-4727-b83c-7f837ca99a66" />


## Live Demo

You can play the game directly in your Web browser here:

