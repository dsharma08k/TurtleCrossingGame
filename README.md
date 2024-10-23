# Turtle Crossing Game

This is a simple Python game using the `turtle` graphics library where the player controls a turtle, attempting to cross a busy road while avoiding oncoming traffic. Each time the turtle crosses the road successfully, the game difficulty increases.

## Game Features

- Player Control: Use the "up arrow key" to move the turtle upwards across the road.
- Cars: Randomly generated cars move horizontally across the screen at varying speeds.
- Scoreboard: The game tracks the player's level, increasing with each successful crossing.
- Game Over: The game ends if the turtle collides with a car.

## File Overview

The game is structured across four Python files:

1. `main.py`: 
   - The main game loop, handling screen setup, player movement, car generation, and collision detection.
   - Key components:
     - Initializes the game window and controls.
     - Runs the game loop, checking for car collisions and if the player reaches the finish line.
     - Increases difficulty by speeding up cars after each successful crossing.
   
2. `car_manager.py`: 
   - Manages the cars, including their creation and movement.
   - Key components:
     - Randomly generates cars and moves them across the screen.
     - Increases car speed as the player's level progresses.

3. `player.py`: 
   - Manages the player's turtle, including movement and detecting if the turtle reaches the finish line.
   - Key components:
     - Moves the turtle forward with the `up` arrow key.
     - Resets the turtle to the starting position after reaching the finish line.

4. `scoreboard.py`: 
   - Handles the scoreboard display, including the current level and game over screen.
   - Key components:
     - Displays the player's current level.
     - Shows a "Game Over" message when the player collides with a car.

## How to Play

1. Run the game using the `main.py` script.
2. Use the **up arrow key** to move the turtle forward.
3. Avoid the moving cars as you attempt to cross the road.
4. Each successful crossing increases your level and the speed of the cars.
5. If the turtle collides with a car, the game ends.
