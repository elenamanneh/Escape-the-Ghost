# Escape the Ghost

## Overview
Escape the Ghost is an Assembly language game project developed as part of the CSCB58 Winter 2024 course at the University of Toronto, Scarborough. The game involves a player navigating through platforms, collecting stars, and avoiding ghosts to reach a door and win the game. The game is designed to run on a bitmap display.

## Game Mechanics
- **Player Movement:** The player can move left, right, and jump. Gravity affects the player's jumping.
- **Platforms:** The game includes multiple platforms that the player can land on and jump from.
- **Stars:** The player needs to collect three stars to open the door and win the game.
- **Ghosts:** Ghosts move within the game, and collision with a ghost results in a loss.
- **Door:** The door starts closed and turns green when all stars are collected, allowing the player to win by reaching it.

## Controls
- **W:** Jump
- **A:** Move left
- **D:** Move right
- **R:** Restart the game
- **Q:** Quit the game
- **G:** Start Ghost Mode
- **N:** Start Normal Mode

## Display Configuration
- **Unit width in pixels:** 8
- **Unit height in pixels:** 8
- **Display width in pixels:** 512
- **Display height in pixels:** 512
- **Base Address for Display:** 0x10008000 ($gp)

## Additional Information
- **Modes:** The game includes Normal Mode and Ghost Mode, with Ghost Mode featuring a moving ghost.
- **Start Screen:** The start screen shows only the platforms, and the player can choose the mode by pressing 'G' for Ghost Mode or 'N' for Normal Mode.

## Project Milestones
1. **Initial Setup:** Game setup with platforms, player character, and additional objects (ghost, stars, door).
2. **Basic Mechanics:** Player movement, jumping, collisions, and gravity implementation.
3. **Game Logic:** Score and conditions for win/loss.
4. **Advanced Features:** Different game modes, moving ghost in Ghost Mode, and start screen functionality.
