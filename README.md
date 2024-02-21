# Snake Game with Reinforcement Learning

## Overview

This is a simple implementation of the classic Snake game using Python, the Pygame library, and reinforcement learning techniques. The game features a snake that moves around the screen eating food, which grows the snake and increases the player's score. The game ends if the snake collides with the walls or itself. The reinforcement learning model is trained to make decisions about the snake's movements based on the current game state.

## Getting Started

1. **Clone the repository**: `git clone https://github.com/yourusername/snake-game.git`
2. **Install Pygame**: `pip install pygame`
3. **Run the game**: `python agent.py`

## Features

- **Simple Controls**: Use the arrow keys to control the snake's direction (up, down, left, right).
- **Reinforcement Learning**: The snake's movements are determined by a reinforcement learning model, which makes decisions based on the current game state.
- **Scoring System**: The player's score increases every time the snake eats food.
- **Game Over**: The game ends if the snake collides with the walls or itself.
- **Game Loop**: The game loop keeps the game running until the player loses or quits.

## Screenshots

![Gameplay Screenshot](screenshots/gameplay.png)

## Known Issues

- Occasionally, the food might spawn in a location that is inaccessible to the snake, leading to a game over.

## Future Enhancements

- Implement a high score system to keep track of the top scores.
- Add different levels of difficulty to make the game more challenging.
- Include power-ups or obstacles to spice up the gameplay.

## Contributing

Contributions are welcome! If you find any bugs or have ideas for improvements, please create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this template to better fit your project's needs!







This code demonstrate how you can use re-enforcement learning to create an ai which can play the popular snake game.


For this to work run the following comands inside your project environment:

pip3 install torch torchvision

pip3 install pygame

pip3 install matplotlib ipython

