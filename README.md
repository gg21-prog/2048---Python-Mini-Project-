# 2048 Game

A Python implementation of the popular 2048 puzzle game using Tkinter for the graphical interface.

## Description

This project is a recreation of the classic 2048 game where players combine numbered tiles to reach the 2048 tile. The game features a 4x4 grid where tiles with the same number merge when moved in the same direction. The goal is to create a tile with the number 2048 before running out of moves.

## Requirements

- Python 3.x
- tkinter (usually comes pre-installed with Python)

## How to Run

Simply execute the Python script:

```bash
python 2048_complete.py
```

## How to Play

- Use arrow keys to move tiles:
  - Left Arrow: Move tiles left
  - Right Arrow: Move tiles right
  - Up Arrow: Move tiles up
  - Down Arrow: Move tiles down

- When two tiles with the same number touch, they merge into one tile with double the value
- After each move, a new tile (value 2) appears in a random empty spot
- The game ends when you create a 2048 tile (win) or when no more moves are possible (lose)

## Features

- Clean graphical interface with color-coded tiles
- Score tracking system
- Win/lose detection
- Smooth gameplay with keyboard controls

## Project Structure

The code is organized into a single file containing:
- Color scheme definitions for different tile values
- Game logic for tile movement and merging
- GUI components using Tkinter
- Game state management

## Technical Details

- Grid Size: 4x4
- Starting tiles: Two tiles with value 2
- New tile value: 2
- Win condition: Creating a 2048 tile
- Lose condition: No valid moves remaining

