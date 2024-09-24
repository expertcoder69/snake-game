# Snake Game

This is a simple implementation of the classic Snake game using Python and the Pygame library.

## Requirements

- Python 3.x
- Pygame

## Installation

1. Install Python from [python.org](https://www.python.org/).
2. Install Pygame using pip:
	```sh
	pip install pygame
	```

## How to Run

1. Clone the repository or download the `app.py` file.
2. Navigate to the directory containing `app.py`.
3. Run the script:
	```sh
	python app.py
	```

## How to Play

- Use the arrow keys to control the direction of the snake.
- The objective is to eat the white fruit to grow the snake and increase your score.
- The game ends if the snake collides with the walls or itself.

## Code Overview

- The game initializes the Pygame library and sets up the game window.
- The snake and fruit are drawn on the screen using rectangles.
- The snake's movement is controlled by the arrow keys.
- The game checks for collisions with the walls and the snake's own body to determine if the game is over.
- The score is displayed on the screen and updated as the snake eats the fruit.

## Functions

- `show_score(choice, color, font, size)`: Displays the current score on the screen.
- `game_over()`: Displays the final score and ends the game.

## License

This project is licensed under the MIT License.
# 
