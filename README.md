# Tic Tac Toe Game in C++

## Introduction

This is a simple console-based Tic Tac Toe game implemented in C++. The game is designed for two players who take turns to mark spaces in a 3×3 grid with either 'X' or 'O'. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

## Features

- A 3×3 grid for the game board.
- Two-player mode with players choosing between 'X' and 'O'.
- Input validation to ensure moves are within bounds and not on already occupied spaces.
- Win detection for rows, columns, and diagonals.
- Draw detection when all spaces are filled and no player has won.

## Rules of the Game

1. Players take turns to place their mark ('X' or 'O') in an empty cell.
2. The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins.
3. If all cells are filled and no player has three marks in a row, the game is a draw.

## How to Play

1. Clone the repository or download the source code.
2. Compile the C++ source code.
3. Run the executable.
4. Follow the on-screen prompts to enter the row and column for your move.

## Compilation and Execution

To compile and run the game, follow these steps:

1. Open a terminal and navigate to the directory containing the source code.
2. Compile the code using a C++ compiler. For example, if you're using `g++`, run:
   ```sh
   g++ -o tictactoe tictactoe.cpp
