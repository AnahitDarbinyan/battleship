# 🚢 Battleship Game in Python

[![Python Version](https://img.shields.io/badge/Python-3.6%2B-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

![Game Preview](assets/battleship_preview.png)

A **classic terminal-based Battleship game** built with Python and Object-Oriented Programming (OOP) principles.  
🎯 Play head-to-head with another player and sink their fleet before they sink yours!

---

## 📁 Project Structure

<pre>Battleship/
├── Board.py       # Manages the game board, hit/miss logic, and display
├── Ship.py        # Defines Ship properties like size, position, and hits
├── Player.py      # Represents each player and their actions
├── game.py        # Main game loop
├── main.py        # The file you need to run
└── README.md      # You're reading it!</pre>

## Getting Started

### Prerequisites

- Python 3.6 or higher installed on your system.

### Run the Game

1. Clone the repository:

```bash
git clone https://github.com/IrenStepanyan/Battleship.git
cd Battleship
````

2. Run the main:

```bash
python main.py
```

## 🎮 Gameplay Overview

* The game is played on a 10x10 grid.
* Each player places their ships on the board.
* Players take turns firing at coordinates (e.g.,5 A).
* The goal is to sink all enemy ships by guessing their positions.

## Main Components

### `Board.py`

* Handles:

  * Creating and displaying the board
  * Tracking hits and misses
  * Checking for valid ship placements

### `Ship.py`

* Handles:

  * Ship size, coordinates, orientation (horizontal/vertical)
  * Checking if the ship is sunk

### `Player.py`

* Handles:

  * Player name
  * Ship placement
  * Choosing attack coordinates
  * Tracking their board and attacks

### `game.py`

* Orchestrates the game flow:

  * Initializes players and boards
  * Controls turn logic
  * Declares the winner

## Features

* Classic two-player mode
* Input validation for coordinates and ship placements
* Board visualization in the terminal
* Hit/miss feedback and win detection

## Future Improvements

* [ ] GUI with `pygame`
* [ ] Save the overall count

Feel free to fork, contribute, or use this project as a foundation for learning object-oriented design in Python!
