# Battleship Game

## Introduction

Battleship Game is a C project where players engage in a thrilling naval battle. Players take turns targeting their opponent's ships on a 10x10 grid, using strategic moves like radar sweeps, smoke screens, and torpedo strikes. The goal? Sink all your opponent’s ships before they sink yours. The game also features bot opponents with three difficulty levels for added challenge.

## Features
### 1.Two-Player Gameplay:
- Players can choose their opponent to be either another person or a bot.
- Traditional turn-based gameplay.
- Ships: Carrier (5 cells), Battleship (4 cells), Destroyer (3 cells), Submarine (2 cells).
### 2.Advanced Moves:
- Radar Sweep: Reveals a 2x2 grid for ship presence.
- Smoke Screen: Hides a 2x2 grid area from radar sweeps.
- Artillery: Targets a 2x2 grid area for attack.
- Torpedo: Targets an entire row or column.
### 3.Tracking Difficulty Levels:
- Easy: Tracks hits and misses.
- Hard: Tracks only hits.
### 4.Bot Integration:
- Implements three difficulty levels: Easy, Medium, and Hard.
- The bot performs better than random and strategically adapts to the gameplay.
### 5.Interactive Grid Display:
Updates dynamically after each turn to reflect hits, misses, and hidden areas.

## How to Play
### Setup:
- Choose between Player vs. Player or Player vs. Bot.
- Place ships (Carrier, Battleship, Destroyer, Submarine) on a 10x10 grid using coordinates and orientation.
- The game randomly selects which player goes first.
### Gameplay:
- Players take turns choosing a move: Fire, Radar Sweep, Smoke Screen, Artillery, or Torpedo.
- Valid moves and inputs are verified, and grids update dynamically.
- Sinking opponent ships unlocks advanced moves.
### Winning Condition:
The game ends when one player sinks all of their opponent's ships

## Requirements
- C Compiler (e.g., GCC)
- Standard Libraries: stdlib.h, stdio.h, string.h, time.h

## Usage
- Compile the program using a C compiler.
- Run the executable.
- Follow on-screen instructions to select game mode and play.
  
## Note
- A detailed high-level description of the game, including test cases and method specifications, is available in the accompanying project report.
