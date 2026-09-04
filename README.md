# 🐍 Snake Game — SDL2

A classic Snake game developed in **C++ using SDL2 and SDL2_ttf**. The player controls the snake, collects food to increase its length and score, avoids moving obstacles, and collects temporary bonus food for additional points.

[![Download Game](https://img.shields.io/badge/Download-Windows%20Executable-blue?style=for-the-badge&logo=windows)](https://github.com/nishatnishu/Snake_Game_SWE-150_Project/releases/tag/v1.0.0)

---

## 🎮 Play the Game (Windows)

No build tools required to play:

1. Go to the **[Latest Release](https://github.com/nishatnishu/Snake_Game_SWE-150_Project/releases/tag/v1.0.0)** page.
2. Download **`Snake_Game_SWE-150_Project-main.zip`**.
3. Extract (unzip) the contents into a folder.
4. Double-click **`main.exe`** to start playing.

---

## ✨ Features

* **Arrow Key Controls:** Smooth movement input.
* **Score Tracking:** Real-time score display rendered with custom TTF fonts.
* **Bonus Food System:** High-value temporary food spawns periodically.
* **Moving Obstacles:** Dynamic obstacles increase gameplay difficulty.
* **Wrap-Around Screen:** Snake teleports to the opposite side when hitting window edges.
* **Custom Graphics:** Circular segment rendering for the snake body.

---

## 🎮 Controls

| Action | Key |
| :--- | :--- |
| **Move Up** | `↑` Up Arrow |
| **Move Down** | `↓` Down Arrow |
| **Move Left** | `←` Left Arrow |
| **Move Right** | `→` Right Arrow |
| **Quit Game** | `Esc` or Close Window |

---

## 📜 Game Rules

* **Regular Food:** Worth **10 points** and increases snake length.
* **Bonus Food:** Spawns every **5 regular foods** collected, lasts for **5 seconds**, and awards **20 points**.
* **Obstacles:** Colliding with any moving obstacle results in immediate **Game Over**.
* **Screen Wrap:** Moving past the edge wraps the snake around to the opposite side.

---

## 📂 Project Structure

```text
Snake_Game_SWE-150_Project/
├── src/                 # Source files and assets
├── Makefile             # Build automation script
├── README.md            # Project documentation
├── SDL2.dll             # SDL2 dynamic library
├── SDL2_image.dll       # SDL2_image dynamic library
├── SDL2_ttf.dll         # SDL2_ttf dynamic library
├── main.cpp             # Game entry point and logic
├── main.exe             # Compiled Windows executable
└── nishat.ttf           # TrueType Font file for UI rendering
