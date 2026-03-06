Rock, Paper, Scissors - Python Game

This README file guides through:

-GitHub Repository
-Library Usage
-Game Instructions

Overview

This project is an implementation of the classic Rock, Paper, Scissors game written in Python. The user plays against the computer, which randomly selects its move each round. The programme validates user input as well as tracks game statistics and allows the player to play multiple rounds until they choose to exit.

Repository

The full source code for this project can be found on GitHub:

GitHub Repository: https://github.com/tal333/rock-paper-scissors-tm

Library Usage

This project only requires the Python standard library. 
The ‘random’ module is used so the computer can randomly choose between Rock, Paper, or Scissors. 
No additional installation is required because ‘random’ comes built-in with Python.

Running the Game

1. Clone or download the respository
2. Navigate to the project folder
3. Run the programme

Game Instructions

1. Enter your name:

Rules for a valid name:
- Must contain only letters
- Must be at least 3 characters long
- You have 5 attempts to enter a valid name

If a valid name is not entered within the allowed attempts, the game will end.

2. Enter your choice:

You will be prompted to choose one of the following input options:
- ‘r’ for Rock
- ‘p’ for Paper
- ’s’ for Scissors
- ‘e’ to Exit the game

If you enter an invalid input, you will be prompted to answer it correctly until you do so.

3. Choose to Play Again

Once you input, the computer will randomly choose a selection of Rock, Paper, or Scissors.
Your choice and the computer’s choice will then be displayed, along with whether you won the round or not, based on the classic Rock, Paper, Scissors rules.

The game keeps track of statistics including wins, losses, and total games played, which will also be displayed as a summary.

After the round of the game, you will be asked whether you would to play again.
Enter ‘y’ if you want to play another round, or ’n’ to end the game.
If you enter an invalid input, you will be prompted to answer it correctly until you do so.

Author

Created by Taline Manuelian

Project developed as part of a Python Game Development assignment.
