# Pong Game

## Overview

This repository contains a Python implementation of the classic arcade game Pong using the SimpleGUI library. The game features a classic two-player mode where players control paddles to keep the ball in play and score points by making the ball pass the opponent's paddle.

## Requirements

To run this game, you will need:

- Python 2.7 or later (the code is written in Python 2)
- SimpleGUI library (part of the CodeSkulptor environment)

## Getting Started

1. **Install Python**: Ensure you have Python installed on your machine. This game is designed for Python 2.7.

2. **SimpleGUI**: SimpleGUI is typically used within the CodeSkulptor environment or similar. If running locally, you might need to adapt the code for other Python GUI libraries, such as Pygame or Tkinter.

3. **Running the Game**: Copy the provided code into a Python file, for example, `pong.py`. Run the file using Python 2.7:

   ```sh
   python pong.py
Note: If using CodeSkulptor, simply paste the code into the CodeSkulptor editor and run it there.

How to Play
Player 1: Use the 'W' key to move the paddle up and the 'S' key to move it down.
Player 2: Use the 'Up' arrow key to move the paddle up and the 'Down' arrow key to move it down.
Restart: Click the "Restart" button to reset the game.
Code Explanation
Global Variables:

WIDTH and HEIGHT: Dimensions of the game canvas.
BALL_RADIUS, PAD_WIDTH, PAD_HEIGHT: Dimensions related to the ball and paddles.
LEFT, RIGHT: Directions used to determine ball movement.
ball_pos, ball_vel: Current position and velocity of the ball.
paddle1_pos, paddle2_pos: Positions of the paddles.
paddle1_vel, paddle2_vel: Velocities of the paddles.
score1, score2: Scores of the two players.
Functions:

spawn_ball(direction): Initializes the ball's position and velocity. The direction parameter determines the initial direction of the ball.
new_game(): Resets the game state, including scores and paddle positions, and starts a new ball.
draw(canvas): Draws the game elements on the canvas and updates game logic, including ball and paddle movements and collisions.
keydown(key): Handles key presses to move paddles.
keyup(key): Stops paddle movement when keys are released.
Contributing
Feel free to fork this repository and make improvements or modifications. If you have any issues or feature requests, please open an issue on the repository's GitHub page.

Acknowledgments
Code example inspired by classic Pong game implementations.
SimpleGUI library used for graphical interface (typically available in CodeSkulptor).
css
Copy code

This `README.md` provides an overview of the game, instructions for running it, and a brief explanat
