# 🕹️ Pygame Circle Game 🎮

This is a simple Pygame where a ball moves within a circle.The objective is to keep the ball inside the circle by bouncing it off a block. The game tracks the duration of each round and the number of times the ball bounces off the block.

## Features 🌟

- ⚽ Ball movement and collision detection
- ⏱️ Game timer to track the duration of each round
- 📊 Tap counter to track the number of bounces off the block
- 💡 Instructions displayed at the start of each game and after each reset

## Installation 🛠️

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/pygame-circle-game.git
    ```
2. Navigate to the project directory:
    ```sh
    cd pygame-circle-game
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## How to Play 🕹️

1. Run the game:
    ```sh
    python main.py
    ```
2. The game starts with a circle in the middle of the screen and a block.
3. The text "Tap spacebar to begin" will appear above the circle.
4. Press the spacebar to start the game.
5. The ball will start moving. Use the block to keep the ball inside the circle.
6. The game will display the time and number of bounces of the previous round after the ball exits the circle.

## Code Structure 🗂️

- `main.py`: Main game loop and event handling
- `configs.py`: Configuration settings for the game
- `assets.py`: Asset loading and management
- `circle.py`: Circle class
- `ball.py`: Ball class
- `block.py`: Block class

## Game Controls 🎮

- `SPACEBAR`: Start the game
- `ARROW KEYS`: Move the block
