# Pong Game with a Single Button Control

## Description

This project is an implementation of the classic Pong game on a Raspberry Pi Pico with an OLED screen. The goal of the game is to bounce the ball using the paddle by controlling its position with a single button. When the button is pressed, the paddle moves up, and when released, the paddle moves down. The game pits the player against an AI that controls the opposing paddle.

## Features

- Control the player's paddle with a single button: press to move up and release to move down.
- The computer's paddle is controlled automatically by an AI to follow the ball.
- Ball and paddles are displayed on an OLED screen.
- A scoring system displays the player's and computer's scores.
- After each point, the game resets with a short pause to display the scores.

## Required Hardware

- Raspberry Pi Pico
- 128x64 OLED display (I2C compatible)
- 1 push-button
- Resistor (10kΩ for pull-up)
- Jumper wires

## Installation

1. **Install MicroPython** on the Raspberry Pi Pico (if not already done).
2. Use **Thonny** or any compatible MicroPython editor to program the Raspberry Pi Pico.
3. **Copy the game file** (e.g., `pong.py`) to the Pico.
4. **Run the script**.

## Usage

1. The OLED screen will display the game field with the player's and computer's paddles, and the ball.
2. **Press the button** to move the player's paddle up.
3. **Release the button** to move the paddle down.
4. The computer's paddle will automatically follow the ball.
5. After each point, the score will be displayed, and the ball will reset to the center of the field.

## Possible Improvements

- Add sound effects for ball collisions or when points are scored.
- Implement a multiplayer mode with two buttons for paddle control.
- Introduce increasing difficulty by making the AI faster as the player scores points.
- Display the score on an LCD or 7-segment display.
- Add a timed challenge mode to score points within a limited time.

## Authors

- **Raphaël Parone**
- **Alain Sliman** - Development & Documentation
