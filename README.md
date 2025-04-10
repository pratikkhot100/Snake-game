# Snake-game
## 🔍 Game Description:
This is a classic Snake game implemented in Java using Swing GUI components (JFrame, JPanel, Timer, etc.). The player controls a snake that grows in length by eating food. The game ends if the snake collides with itself or the wall.

## 🎯 Game Objective:

- Control the snake using arrow keys.
- Eat the food (randomly appearing).
- Each food increases the snake’s length and score.
- Avoid crashing into the wall or the snake’s own body.

## 📸 Screenshot:

![image](https://github.com/user-attachments/assets/2c90dfe3-5f46-4f6b-90a7-a106d1be99d3)

## 🛠️ Tech Stack:

- Java SE (8+)
- Swing (GUI)
- AWT (for graphics and event handling)

## ⚙️ Game Features:

- Real-time movement using Timer and key listeners.
-  Score system based on how much food is eaten.
- Collision detection (walls & self).
- Restart functionality.
- Java Swing-based GUI using:
- JFrame (main window)
- JPanel (game area)
- Graphics (drawing snake, food, score)

## 📄 How the Game Works (Flow):

- Snake starts moving in a direction.
- Player controls it using arrow keys (up, down, left, right).

- If snake eats food:

Grows longer.

Score increases.

New food is generated randomly.

- If snake hits:

Wall or itself → game over.

Press R to restart after game over.
