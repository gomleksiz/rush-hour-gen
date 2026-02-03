# Rush Hour Puzzle Generator

Generate solvable Rush Hour sliding block puzzles with customizable car configurations.

## Features

- **Configurable car collection**: Set your own number of small cars (2-cell) and trucks (3-cell)
- **Guaranteed solvable**: BFS solver verifies every puzzle has a solution
- **Difficulty ratings**: Easy, Medium, Hard based on minimum moves required
- **Print-friendly**: 4 cards per page, clean layout for printing
- **Square 6x6 grid**: Accurate representation of the classic Rush Hour board

## How to Play Rush Hour

1. The goal is to move the RED car to the exit on the right side (row 3)
2. Cars can only move forward/backward along their orientation (horizontal cars move left/right, vertical cars move up/down)
3. Cars cannot pass through each other
4. Find the sequence of moves to clear a path for the RED car

## Live Demo

[Play the generator here](https://gomleksiz.github.io/rush-hour-gen/)

## Usage

1. Set the number of small cars and trucks you have
2. Click "Generate New Puzzles" to create 4 random solvable puzzles
3. Click "Print Cards" to print them for offline play

## Technical Details

- Pure HTML/CSS/JavaScript - no dependencies
- BFS (Breadth-First Search) solver finds optimal solution
- Puzzles are generated with intentional blockers on row 3 for non-trivial solutions
- Minimum 4 moves required for each generated puzzle
