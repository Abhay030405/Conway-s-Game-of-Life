# Conway's Game of Life

Conway's Game of Life is a cellular automaton devised by the British mathematician John Horton Conway. This project implements the simulation in Python using object-oriented programming principles and provides both visual and console-based representations of the evolving grid.

## 📌 Project Overview

This simulation follows the rules of Conway's Game of Life:

- Any live cell with 2 or 3 live neighbors survives.
- Any dead cell with exactly 3 live neighbors becomes a live cell.
- All other live cells die, and all other dead cells stay dead.

Implemented in Python using basic OOP concepts, list operations, and visualization using `matplotlib`.

## ✅ Features

- Create and initialize a custom grid of any size.
- Populate the grid with live cells at specific coordinates.
- Step-by-step evolution of the grid.
- Run multiple steps at once.
- Console-based and graphical visualization of the grid.

## 🧱 Project Structure

- `__init__` : Initializes the grid with all cells dead.
- `make_step()` : Applies the Game of Life rules to update the grid by one generation.
- `make_n_steps(n)` : Runs the game for `n` steps.
- `draw_grid()` : Displays the current grid using `matplotlib`.
- `print_grid()` : Prints the current grid to the console.
- `get_grid()` : Returns the current grid state.

## 🛠️ Requirements

- Python 3.x
- matplotlib

You can install required libraries with:

```bash
pip install matplotlib