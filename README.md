# 🐍 Snake Game — SDL2

A classic Snake game developed in **C++ using SDL2 and SDL2_ttf**. The player controls the snake, collects food to increase its length and score, avoids obstacles, and can collect temporary bonus food for additional points.

## Features

* Snake movement using arrow keys
* Regular food collection and snake growth
* Score tracking
* Temporary bonus food system
* Moving obstacles
* Collision detection
* Screen wrap-around
* Custom snake rendering using circular shapes
* Score display using SDL2_ttf

## Technologies

* **C++**
* **SDL2**
* **SDL2_ttf**
* **C++ STL**

## Controls

| Action     | Key          |
| ---------- | ------------ |
| Move Up    | `↑`          |
| Move Down  | `↓`          |
| Move Left  | `←`          |
| Move Right | `→`          |
| Quit       | Close Window |

## Game Rules

* Collecting regular food increases the score by **10 points**.
* Every **5 foods** collected activates bonus food.
* Bonus food is available for **5 seconds**.
* Collecting bonus food awards **20 points**.
* The snake grows when food is collected.
* Colliding with an obstacle ends the game.
* The screen wraps around when the snake reaches an edge.

## Project Structure

```text
SDL-Snake-Game/
│
├── main.cpp
├── nishat.ttf
└── README.md
```

## Requirements

* C++ compiler
* SDL2
* SDL2_ttf
* Compatible desktop environment

## Build & Run

Make sure SDL2 and SDL2_ttf are installed and configured.

Example compilation command:

```bash
g++ main.cpp -o SnakeGame -lSDL2 -lSDL2_ttf
```

Run:

```bash
./SnakeGame
```

On Windows:

```bash
SnakeGame.exe
```

> Ensure the required SDL2 DLL files and `nishat.ttf` font are available in the appropriate location when running the application.

## Game Components

The project implements the following core components:

* **Snake:** Stores the snake body and movement direction.
* **Food:** Handles regular food generation.
* **Bonus Food:** Provides temporary high-value food.
* **Obstacles:** Moving obstacles that increase gameplay difficulty.
* **Collision Detection:** Detects collisions between the snake and obstacles.
* **Rendering:** Uses SDL2 to render the snake, food, obstacles, and score.
* **Game Loop:** Handles input, game updates, rendering, and timing.

## Author

**Nishat Tasnim**

Software Engineering Student

## Project Highlights

* C++ game development
* SDL2 graphics programming
* Event-driven input handling
* Real-time game loop
* Collision detection
* Dynamic object movement
* Score and game-state management
* Modular data structures using C++ STL
