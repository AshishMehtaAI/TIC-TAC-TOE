# Java Tic Tac Toe Game

This is a simple console-based Tic Tac Toe game implemented in Java.

## How to Play

1. *Compile and Run:*
   - Make sure you have Java installed on your system.
   - Open a terminal or command prompt and navigate to the directory containing the `.java` files.
   - Compile the program using the command:
     bash
     javac TicTacToe.java
     
   - Run the program using the command:
     bash
     java TicTacToe
     

2. *Game Rules:*
   - The game is played on a 3x3 grid.
   - Two players take turns to mark a square with their symbol ('X' or 'O').
   - The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.
   - If the grid is filled and no player has won, the game is declared a draw.

3. *Gameplay:*
   - The game prompts the players to input their moves.
   - Input should be in the format `row column`, where `row` and `column` are numbers from 1 to 3 (e.g., `2 2` for the center square).
   - The game will display the updated board after each move.

## Features

- The game prevents invalid moves (e.g., choosing a square that is already occupied).
- It correctly identifies the winner or a draw and displays the result.

## Contributing

If you'd like to contribute to this project, please fork the repository and then create a pull request with your changes.
