# Ping-Pong-Ball-Game_C+
A simple Pong game built in C++ using Raylib. Features classic paddle-ball mechanics with smooth gameplay and easy-to-read code for learning and experimentation.
✨ Features

Classic paddle-and-ball mechanics

Player vs CPU mode with simple AI

Score tracking system

Smooth ball physics and collision handling

Clean, modular, and beginner-friendly C++ code

📂 Project Structure
├── main.cpp        # Source code for the game
├── README.md       # Project documentation

⚙️ Requirements

C++ Compiler (g++, clang, MSVC, etc.)

Raylib library installed

🚀 How to Build & Run
1. Clone the Repository
git clone https://github.com/your-username/pong-game.git
cd pong-game

2. Compile the Game

If you have Raylib installed globally:

g++ main.cpp -o pong -lraylib -lGL -lm -lpthread -ldl -lrt -lX11


On Windows (MinGW example):

g++ main.cpp -o pong.exe -O2 -Wall -std=c++17 -I path\to\raylib\include -L path\to\raylib\lib -lraylib -lopengl32 -lgdi32 -lwinmm

3. Run the Game
./pong

🎮 Controls

Arrow Up (↑) → Move paddle up

Arrow Down (↓) → Move paddle down


CPU paddle moves automatically

📸 Screenshot
