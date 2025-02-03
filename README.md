# Cellular-Automata

## Overview
This repository contains a Jupyter Notebook that implements two well-known **cellular automata** models:

1. **Toom’s Rule**: A **nonlinear majority voting cellular automaton**.
2. **Conway’s Game of Life**: A famous **zero-player game** with emergent complex behaviors from simple local rules.

Both simulations run on a square lattice, where each cell updates based on specific rules.

---

## How It Works

### 1. **Toom’s Rule**
Toom’s Rule follows an update function where each cell is determined by the **majority** value of itself, the **top neighbor**, and the **left neighbor**:

### 2. **Conway’s Game of Life**
Each cell in the grid follows these simple rules:
- **Survival**: A live cell with **2 or 3** neighbors stays alive.
- **Death**: A live cell with **<2 (underpopulation)** or **>3 (overpopulation)** neighbors dies.
- **Birth**: A dead cell with exactly **3 neighbors** becomes alive.

These simple rules create **complex structures** like pulsars, spaceships, and gliders.

![Toom](https://github.com/gbr-pinna/Cellular-Automata/Toom.gif)
![Pulsar](https://github.com/gbr-pinna/Cellular-Automata/Pulsar.gif)
