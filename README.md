# Snake Game in Python with Pygame 🐍🕹️

This is a simple implementation of the classic Snake game in Python using the Pygame library. The game features a snake that moves around the screen, eating food to grow longer. The player's goal is to control the snake and make it as long as possible without colliding with the game boundaries or itself.

## How to Play

1. Install Python: If you don't already have Python installed, download and install it from [python.org](https://www.python.org/downloads/).

2. Install Pygame: You'll need to have the Pygame library installed. You can install it using pip:

   ```bash
   pip install pygame
   ```

3. Clone the Repository: Clone or download this repository to your local machine.

4. Run the Game: Open your terminal, navigate to the repository's directory, and run the following command:

   ```bash
   python main.py
   ```

5. Gameplay:
   - Use the arrow keys (Up, Down, Left, and Right) to control the snake's direction.
   - The snake will grow in length when it eats the green food.
   - The game ends when the snake collides with the boundaries or itself.
   - A pop-up message will appear with your score, and you can choose to play again.

## Code Explanation

- The game is implemented using object-oriented programming. It consists of two main classes: `Cube` and `Snake`, which represent the game objects.

- The game window is created using Pygame, and the snake and food are drawn and updated in the game loop.

- The snake's movement is controlled by the arrow keys, and it can change direction but cannot move backward.

- A game over message box appears when the snake collides with the boundaries or itself.
