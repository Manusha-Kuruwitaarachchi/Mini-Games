Math Quiz Game
Description

This repository contains a simple math quiz game implemented in Python. The game generates a series of arithmetic problems for the user to solve. The problems involve basic operations (addition, subtraction, multiplication) with randomly generated operands within a specified range.
How to Play

    Run the script.
    Press 
Enter to start the game.
    Solve the presented arithmetic problems by typing your answers and pressing Enter.
    If you wish to exit the game early, type 'e' and press Enter.
    The game will display the total time taken, the number of correct answers on the first attempt, the number of correct answers after additional attempts, and the number of wrong answers.

Game Rules

    The game consists of 10 arithmetic problems by default.
    For each problem, you have two attempts to provide the correct answer.
    If the answer is correct on the first attempt, it is counted towards the correct
first
attempt score.
    If the answer is correct on the second attempt, it is counted towards the correct
after
attempts score.
    Incorrect answers are tracked and displayed at the end of the game.

Constants

The following constants are defined in the script:

    OPERATORS: List of arithmetic operators used in the problems (+, -, *).
    MIN_OPERAND: Minimum value for operands.
    MAX_OPERAND: Maximum value for operands.
    TOTAL_PROBLEMS: Total number of problems in the game.

Exiting the Game

To exit the game before completing all problems, type 'e' and press Enter. The game will display the results up to that point and end.
Results Display

At the end of the game, the following results are displayed:

    Total time taken to complete the game.
    Number of correct answers on the first attempt.
    Number of correct answers after additional attempts.
    Number of wrong answers.
