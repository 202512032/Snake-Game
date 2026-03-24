# Snake Game (C++)

This is a simple console-based Snake game I built in C++. The goal is to control the snake, eat food, and grow as long as possible without hitting the wall or yourself.

## What it does
- Snake moves continuously in the terminal
- You can control it using arrow keys or WASD
- Eating food increases the score and snake length
- Game speed increases gradually
- Game ends on collision
- Option to restart or quit

## How to run

Compile:
g++ snake_game.cpp -o snake

Run:
./snake

## Controls
- W / ↑ → Up  
- S / ↓ → Down  
- A / ← → Left  
- D / → → Right  
- R → Restart  
- Q → Quit  

## Notes
This version works on Linux/Mac because it uses termios for handling input.


