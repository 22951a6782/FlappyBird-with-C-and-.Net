# 🐦 Flappy Bird - Windows Forms Clone

A simple clone of the classic Flappy Bird game built using **C#** and **Windows Forms**. The game features basic gravity mechanics, score tracking, collision detection, and increasing difficulty.

---

## 🎮 Features

- Smooth gravity and movement controls
- Pipe collision detection
- Score counting and display
- Game over detection
- Increasing difficulty as the score increases

---

## 🛠️ Technologies Used

- **Language:** C#  
- **Framework:** .NET Windows Forms  
- **IDE:** Visual Studio  
- **Graphics:** Static image resources (e.g., bird, pipes, ground)  

---

## 📁 Project Structure

![image](https://github.com/user-attachments/assets/1ea0a2a4-ca38-4037-9120-277cbd48e13b)



---

## 🧠 Game Logic Overview

- **Gravity Control:**
  - When spacebar is pressed, gravity becomes negative (bird goes up)
  - When released, gravity resets to positive (bird falls)

- **Obstacle Movement:**
  - Pipes (`pipeTop` and `pipeBottom`) move leftward across the screen
  - When off-screen, they reset to the right and score increases

- **Collision Detection:**
  - If the bird hits any pipe, the ground, or goes out of bounds — game ends

- **Score Logic:**
  - Increments when pipes are successfully passed
  - Pipe speed increases after score > 5 to increase difficulty

---

## ⌨️ Controls

- **Spacebar Pressed:** Bird flies upward  
- **Spacebar Released:** Bird falls down  

---

## 📸 Screenshots

> You can insert screenshots of the game UI here (e.g., during play, game over screen).

---

## 🚀 How to Run

1. Open the solution in **Visual Studio**
2. Make sure all image resources (`bird`, `pipe`, `pipedown`, `ground`) are added correctly in the Resources folder
3. Press `Start` or `F5` to run the game

---

## 🙋 Author

**Developed by:** *perala pranitha*  
If you liked this project or want to enhance it, feel free to fork and improve!


