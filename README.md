# Space Invaders Game

This project implements a classic Space Invaders game using JavaScript and HTML5 Canvas.

## Overview

The game involves controlling a spaceship at the bottom of the screen, moving it horizontally to avoid incoming projectiles and shooting at descending alien invaders. The objective is to survive as long as possible while earning points by destroying invaders.

## Features

- **Player Control**: Use arrow keys (`←` and `→`) to move left and right. Press `Space` to shoot.
- **Invader Movement**: Invaders move horizontally across the screen and descend periodically.
- **Projectile Mechanics**: Players and invaders can shoot projectiles that collide with targets.
- **Grid System**: Invaders move as a group in a grid pattern, changing direction upon reaching screen edges.
- **Scoring**: Earn points for each invader destroyed. Displayed score updates in real-time.

## Game Elements

- **Canvas and Context Setup**: Initialize canvas for rendering game graphics.
- **Player Class**: Controls the player's spaceship movement and shooting.
- **Projectile Class**: Manage projectiles fired by both player and invaders.
- **Invader and Grid Classes**: Define invader behavior and grid movement logic.
- **Collision Detection**: Handle collisions between projectiles, player, and invaders.
- **Visual Effects**: Implement particle animations for explosions and background visuals.

## Setup and Usage

To run the game locally:

1. Clone this repository.
2. Open `index.html` in a web browser that supports HTML5 Canvas.
3. Use arrow keys (`←` and `→`) for left and right movement.
4. Press `Space` to shoot projectiles at the invaders.


## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

Enjoy playing Space Invaders and have fun exploring the game mechanics and features!
