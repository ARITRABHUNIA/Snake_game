# Snake Game

This project is a simple implementation of the classic Snake game using HTML, CSS, and JavaScript. The game allows users to control a snake using keyboard arrows, with the objective of eating fruits to grow longer and achieve higher scores.

## Getting Started

### Prerequisites

To run this game, you need a web browser with JavaScript enabled. No additional software or libraries are required.

### Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/snake-game.git
    cd snake-game
    ```

2. **Open the Game:**

    Open the `index.html` file in your preferred web browser.

### Files

- **index.html:** Contains the structure of the web page.
- **style.css:** Contains the styling for the game.
- **script.js:** Contains the JavaScript code for the game's functionality.

## How to Play

1. **Start the Game:**

    Open the `index.html` file in your web browser. You'll see a welcome message and instructions to start the game by pressing any arrow key.

2. **Control the Snake:**

    Use the arrow keys on your keyboard to control the direction of the snake:
    - Up Arrow: Move up
    - Down Arrow: Move down
    - Left Arrow: Move left
    - Right Arrow: Move right

3. **Objective:**

    The goal is to eat the green fruits that appear on the grid. Each time the snake eats a fruit, it grows longer and the score increases. The game speed increases as the score goes up.

4. **Game Over:**

    The game ends if the snake runs into itself or the walls. The final score will be displayed. Click the "RESTART" button to play again.

## Code Overview

### HTML

The HTML file defines the structure of the web page, including the game container, score display, and restart button.

### CSS

The CSS file styles the game elements, including the snake, fruits, and game area.

### JavaScript

The JavaScript file implements the game logic, including:

- **createGrid:** Creates the grid for the game.
- **createBody:** Initializes the snake body.
- **control:** Handles the arrow key inputs to change the direction of the snake.
- **changeDirection:** Updates the snake's position based on the direction.
- **generateFruit:** Places a fruit at a random position on the grid.
- **fruitGen:** Continuously generates fruits at intervals.
- **startGame:** Initializes and starts the game.
- **restartGame:** Resets the game state for a new game.

## Customization

You can customize the game by modifying the CSS for different styles or adjusting the JavaScript for different behaviors, such as changing the grid size, snake speed, or fruit appearance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project is inspired by the classic Snake game and is developed as a fun exercise to learn and practice HTML, CSS, and JavaScript.

---

Enjoy playing the Snake game and feel free to modify and improve it! If you have any questions or suggestions, please feel free to reach out.

---

