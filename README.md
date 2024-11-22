Snake Game
A simple and interactive Snake game built using Python's turtle module. The player controls the snake to eat food, avoid colliding with walls, and not run into its own tail. The score increases as the snake eats food and extends its body.

Features
Snake Movement: Control the snake's movement using arrow keys (Up, Down, Left, Right).
Food: The snake eats food, which randomly appears on the screen, causing the snake to grow longer.
Scoreboard: Displays the current score and the high score. The high score is saved to a file and persists between game sessions.
Game Over: The game resets if the snake collides with the wall or its own tail.
Files
snake.py: Contains the logic for the snake, including movement, growth, and reset functionality.
food.py: Handles the food object, including random placement and appearance.
scoreboard.py: Manages the score display, including reading and updating the high score.
input.txt: Stores the high score.
main.py: The main script that runs the game.
How to Play
Run the Game: Execute main.py.
Control the Snake: Use the arrow keys:
Up Arrow to move up.
Down Arrow to move down.
Left Arrow to move left.
Right Arrow to move right.
Eat the Food: The snake grows longer as it eats food and the score increases.
Game Over: The game ends if the snake hits a wall or its own tail. The score is reset, and the game restarts.
