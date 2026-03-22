# C++ Console-Based Game Collection

This project is a small collection of console-based games written in C++.
I built this while practicing OOP concepts and basic algorithms, and tried to make everything interactive and fun to play in the terminal.

It includes:

* Tic Tac Toe (with multiplayer + series mode)
* Maze Runner (random maze + shortest path logic)
* Knight’s Tour game

---

## Features

* Fully interactive console gameplay
* Object-Oriented Design (classes, inheritance, polymorphism)
* Random maze generation using DFS
* Shortest path calculation using BFS
* Score system based on efficiency and time (Maze Runner)
* Clean modular structure for each game

---

## Games Included

### 1. Tic Tac Toe

* 2-player game
* Supports "best of 1 / 3 / 5" series
* Highlights winning cells
* Keeps track of score across rounds

---

### 2. Maze Runner

* Generates a random maze every time
* Player moves using **W A S D keys**
* Calculates minimum possible moves
* Shows performance score based on:

  * moves taken
  * time

---

### 3. Knight’s Tour

* Player manually moves the knight
* Goal: visit every cell exactly once
* Ends when no moves are left or board is completed

---

## Tech Used

* C++
* STL (vector, queue, algorithms)
* OOP concepts
* DFS (for maze generation)
* BFS (for shortest path)

---

##  Quick Run

```bash
# Clone the repository
git clone https://github.com/Sujal-HB/Triplay-Console.git
cd Triplay-Console

# Compile the project
g++ file1.cpp -o game

# Run the game
./game

```
