# Snake Game

A classic Snake Game implemented in Java using basic Object-Oriented Programming (OOP) concepts and Swing for the graphical user interface.

## Table of Contents

- [Introduction](#introduction)
- [Concepts Used](#concepts-used)
- [Installation](#installation)
- [How to Run the Game](#how-to-run-the-game)
- [Game Controls](#game-controls)
- [Gameplay](#gameplay)
- [Project Structure](#project-structure)
- [Credits](#credits)
- [License](#license)

## Introduction

This project is a simple implementation of the classic Snake Game. The game is built using Java and Swing, showcasing basic OOP principles. The snake grows longer each time it eats an apple, and the game ends if the snake collides with itself or the walls.

## Concepts Used

The project demonstrates the following concepts:

- **Object-Oriented Programming (OOP)**: The game is structured using classes and objects.
- **Inheritance**: The `Board` class extends `JPanel` and implements `ActionListener` for handling game events.
- **Event Handling**: The game uses key events to control the snake's movement and a timer for game progression.
- **Swing**: Java Swing is used for creating the game window and rendering graphics.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/snake-game.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd snake-game
    ```
3. **Compile the Java files**:
    ```bash
    javac -d bin src/snakegame/*.java
    ```
4. **Run the game**:
    ```bash
    java -cp bin snakegame.Main
    ```

## How to Run the Game

After compiling and running the game, a window will open displaying the game board. The game starts immediately, and you can control the snake using the arrow keys on your keyboard.

## Game Controls

- **Arrow Keys**: Use the arrow keys to change the direction of the snake.
    - **Left Arrow**: Turn left
    - **Right Arrow**: Turn right
    - **Up Arrow**: Move up
    - **Down Arrow**: Move down

## Gameplay

- The snake moves continuously in the current direction.
- Each time the snake eats an apple, it grows longer.
- The game ends if the snake collides with itself or the walls of the window.
- The game window is 300x300 pixels, and each segment of the snake (and the apple) is 10x10 pixels.

## Project Structure

- **`src/snakegame/Board.java`**: The main game logic including rendering, movement, and collision detection.
- **`src/snakegame/Main.java`**: The entry point of the game that sets up the game window.
- **`src/snakegame/icons/`**: Contains the images used for the snake's head, body, and apples.

## Credits

- **Images**: Icons for the apple, dot, and snake head are used from the `icons` directory.
- **Java Swing**: The game utilizes Java Swing for the graphical user interface.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
