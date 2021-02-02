# Checkers AI Game

## Technologies Used

* Java

## Summary of Project
* This is a project to create an AI for a game of Checkers using Minimax, Alpha-Beta Minimax & Heuristic Minimax.
* First I created both a 4X4 and 8X8 board on which two Human players could play a game of Checkers.
* Next I created a Random AI to play Checkers against. This AI played valid moves randomly.
* Then, I implemented the Minimax Algorithm and created an AI to make intelligent decisions.
* Lastly, I implemented more efficient Minimax Algorithms (Alpha-Beta Minimax & Heuristic Minimax) to make Intelligent decisions.

## How to Play/Rules

1. Enter “b” or “w” to select player (Only lowercase)
2. Enter 4 or 8 to choose board size
3. Choose 1 or 2 to choose the AI you want to play against
4. Enter moves like “A2-B1” (Note enter in uppercase only)

Input Format:
For moves you can use the syntax “A1-B2” (Note enter in uppercase only)
For jumps & multiple jumps you can use the syntax “A1-C3”

Rules:
Black starts first. You can only move diagonally and jump if there’s an opponent’s piece which it can capture. If you have a capture available, you must perform the jump.

Game Decision:
If the opponent has no more pieces on the board, you win!
If there are no possible moves left, the game ends.

Tie conditions: 
For 4x4 board: When move count exceeds 10 moves/ player.
For 8x8 board: When move count exceeds 30 moves/ player.

## Future Work

* Create a GUI for the game created.
* Create an AI for Chess as it uses similar, but more complicated ideas since different pieces move differently.


