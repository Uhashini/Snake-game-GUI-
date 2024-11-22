# Snake Game

## Overview
This is a Python implementation of the classic Snake game, created using the **Turtle Graphics** library. The game involves controlling a snake that moves across the screen to eat food, causing the snake to grow longer each time. The goal is to avoid collisions with the wall or the snake’s own body. If the snake collides, the game resets.

This project was built as part of the **100 Days of Code** challenge under the guidance of **Dr. Angela Yu**.

## Features
- **Snake Movement**: Controlled via the keyboard using the arrow keys (`Up`, `Down`, `Left`, `Right`).
- **Random Food Generation**: The snake eats food that appears randomly on the screen to grow longer.
- **Score Tracking**: Displays the current score and the highest score achieved across sessions.
- **Game Over**: The game resets if the snake collides with its tail or the screen border.
- **High Score**: When the game ends, the highest score is saved to a file (`data.txt`) for future games.

## Installation & Setup

1. **Clone the repository**:

    ```bash
    $ git clone https://github.com/Uhashini/Snake-game-GUI-.git
    ```

2. **Navigate into the project directory**:

    ```bash
    $ cd Snake-game-GUI-
    ```

3. **Install Python**: This project is built using Python 3.11. Make sure Python is installed on your system.

4. **Run the game**: Open the project folder in your preferred IDE (e.g., PyCharm), then run the program.

    ```bash
    $ python snake_game.py
    ```

## Game Instructions
- **Move the snake** using the arrow keys on your keyboard:
  - `Up Arrow`: Move the snake up
  - `Down Arrow`: Move the snake down
  - `Left Arrow`: Move the snake left
  - `Right Arrow`: Move the snake right
- **Objective**: Eat the food (green circle) to grow the snake.
- **End of Game**: If the snake collides with the wall or its own body, the game ends and resets.

## How It Works
- The game is powered by **three main classes**:
  - **Snake**: Controls the snake's creation, movement, and growth.
  - **Food**: Handles the random placement of food that the snake consumes.
  - **Scoreboard**: Manages the current score and high score, saving the highest score to `data.txt`.

- The game screen is managed using the **Turtle graphics** library, and the screen updates every 0.1 seconds to reflect the snake's movement and the food's new positions.

- When the snake eats food, it extends by one segment and the score increases by 1. If the snake collides with the wall or itself, the game resets, and the score is checked against the high score.

## File Structure
- `snake_game.py`: The main game script.
- `input.txt`: A file to store the high score.

## Screenshots

![Snake Game Screenshot](Snake%20game/9d50a764-0003-4949-b870-8dfaeadf2139.jpg)

## Author
This project was developed by **[Uhashini N](https://www.linkedin.com/in/uhashini-n-3b144a291/)**, under the mentorship of **[Dr. Angela Yu](https://www.udemy.com/user/4b4368a3-b5c8-4529-aa65-2056ec31f37e/)** as part of the **100 Days of Code** challenge.
