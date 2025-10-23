# 💎 Raylib Match-3 Game

A simple, complete implementation of the classic Match-3 puzzle game built in **pure C** using the **raylib** library. This project focuses on demonstrating core game mechanics, including state management, cascading tile physics, and dynamic scoring.

***

## ✨ Features

* **Core Match-3 Logic:** Detects and clears horizontal and vertical matches of 3 or more tiles.
* **Physics:** Implements gravity-based tile falling (`fall_offset`) and board refilling.
* **Game States:** Manages game flow using `IDLE`, `ANIMATING`, and `MATCH_DELAY` states for smooth transitions.
* **Scoring System:** Tracks score and uses temporary, animated score pop-ups for visual feedback upon a match.
* **Audio:** Includes basic background music streaming and a sound effect for matches.
* **Minimal Dependencies:** Built entirely with pure C and raylib.

***

## 🚀 How to Play (Standalone Executable)

The easiest way to play is to download the compiled game from the Releases section. No installation or setup is required!

1.  Go to the **[Releases](https://github.com/lahkopo/C-Raylib-Match3/releases)** page of this repository.
2.  Download the latest **`Match3-v1.0.zip`** file.
3.  **Extract** the contents of the ZIP file to any folder.
4.  Double-click **`match3.exe`** to start the game.

### Controls

| Action | Control |
| :--- | :--- |
| **Select Tile** | Left Click on a tile. |
| **Swap Tile** | Left Click on an adjacent tile to the selected one. |

***

## 🛠️ Building from Source

If you want to modify or compile the game yourself, you will need a C compiler and the raylib development libraries.

### Prerequisites

* **Visual Studio** (Recommended for easy setup).
* **raylib** library installed and configured for your environment.

### Build Steps (Visual Studio)

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/lahkopo/C-Raylib-Match3.git](https://github.com/lahkopo/C-Raylib-Match3.git)
    cd C-Raylib-Match3
    ```

2.  **Open Solution:**
    Open the solution file: **`match3.sln`**.

3.  **Build:**
    * Set the configuration to **`Release`** and **`x64`**.
    * Go to **Build** > **Build Solution** (or press `F7`).

4.  **Run:**
    The executable will be located in the `x64/Release/` folder. Ensure the **`assets`** folder and the **`raylib.dll`** file are in the same directory as your compiled `match3.exe` before running.
