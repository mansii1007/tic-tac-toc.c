# Tic Tac Toe

A simple console-based Tic-Tac-Toe game written in C.
Two players take turns, and the program detects a win or a draw automatically.

## How it works

- The board shows numbers from 1 to 9.
- Players take turns entering a position number.
- The selected position is marked with **X** or **O**.
- The game checks for a winner after every move.
- If all positions are filled without a winner, the game ends in a draw.

## Features

- Two-player gameplay
- Board redrawn after each move
- Win detection (rows, columns, diagonals)
- Draw detection
- Input validation for invalid or already-taken spots

## How to run

```bash
gcc tic_tac_toc.c -o tictactoe
./tictactoe
```

## Tech stack

C language
