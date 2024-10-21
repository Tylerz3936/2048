# 2048 Game

A simple implementation of the classic 2048 game in JavaScript, HTML, and CSS. The goal is to combine tiles with the same numbers to reach the 2048 tile, or as high a score as possible.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Code Structure](#code-structure)

## Features
- Basic 2048 gameplay logic
- Score tracking
- Arrow key controls for tile movement (up, down, left, right)
- Dynamic tile creation and merging
- Random generation of new tiles (value of 2)
- Responsive tile styling based on values

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/Tylerz3936/2048.git
   ```

2. Navigate to the project directory:
    ```
    cd 2048
    ```
3. Open index.html in your browser to start the game:

## How to Play
- Goal: Combine the numbered tiles to reach the 2048 tile or higher.
- Use the arrow keys to slide the tiles:
    - Left arrow: Moves all tiles left.
    - Right arrow: Moves all tiles right.
    - Up arrow: Moves all tiles up.
    - Down arrow: Moves all tiles down.
- When two tiles of the same value collide, they merge into one tile with the combined value.
- After each move, a new tile with a value of 2 will appear in a random empty spot on the board.
- The game is over when no more moves are possible.

## Code Structure
- index.html: The main HTML file that sets up the structure of the game.
- styles.css: Contains the styling for the game grid and tiles.
- scripts.js: JavaScript file that handles the game logic, tile movement, and score tracking.

## Key JavaScript Functions:
- setGame(): Initializes the game board.
- slideLeft(), slideRight(), slideUp(), slideDown(): Handle the tile movements in the respective directions.
- setTwo(): Adds a new tile with value 2 in a random empty spot.
- updateTile(): Updates the tile appearance based on its value.
- hasEmptyTile(): Checks if there is at least one empty tile on the board.