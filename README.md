# Hungry Man

A terminal-based arcade game, built entirely in standard C. 

This project demonstrates custom game loop mechanics, 2D array physics, and memory-buffered rendering, without the use of external game engines.

## ✨ Features

* **Custom Game Loop:** Implements real-time input handling and game state updates.
* **Double-Buffered Rendering:** Utilizes a custom memory buffer (`char screen_buffer`) to write the map, entities, and UI to memory before pushing to standard output. This completely eliminates terminal flickering and ensures buttery-smooth frame rates.
* **Entity Collision Physics:** Uses Manhattan distance calculations for precise collision detection between the player, ghosts, and food.
* **Boundary Wrap-Around:** Players can walk through the edges of the map and seamlessly teleport to the opposite side.
* **Autonomous AI:** Features erratic, bouncing ghost enemies that react to map boundaries.

## Controls

* `W` - Move Up
* `S` - Move Down
* `A` - Move Left
* `D` - Move Right
* `Q` - Quit Game

## GamePlay 

<img width="1153" height="594" alt="image" src="https://github.com/user-attachments/assets/f1b3971f-6c87-45c6-a9ab-ce7169b7defa" />


## Getting Started

### Prerequisites
* A C compiler (like GCC or MinGW)
* A Windows operating system (relies on `<windows.h>` and `<conio.h>` for real-time keystroke detection and rendering pacing)

### Compilation & Execution
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/yourusername/hungry-man.git](https://github.com/yourusername/hungry-man.git)

2. Run gcc HUNGRY_MAN.c -o hungry_man for compilation

3. Then, run *start hungry_man.exe*
