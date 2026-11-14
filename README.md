
# Stasis Ball

Stasis Ball is a physics-based arcade puzzle game made for **Hack Club Haven**. Guide a moving ball through each level, avoid hazards, and reach the green goal. Use Stasis to stop the ball, build up a direction, and launch it toward the next opening.

### How to Play

1. The ball moves automatically.
2. Press Space to activate Stasis and pause the ball.
3. While Stasis is active, use the arrow keys or WASD to build launch force in a direction.
4. Press Space again to release Stasis and launch the ball. Stasis also ends when its timer runs out.
5. Reach the green goal to clear the level.
6. Choose one of the three upgrades offered after each completed level by pressing 1, 2, or 3.

Avoid the red hazards. Touching one restarts the current level.

### Think Outside the Level

Sometimes the normal approach will not be enough. You may have to break the game, exploit its physics, or find an unexpected way to get past a level. There is no single correct solution and no limit to how creative you can be. Experiment with Stasis, momentum, and collisions. If you can make it to the goal, it counts.

### Controls

| Key | Action |
|---|---|
| Space | Activate or release Stasis |
| Arrow keys or WASD | Charge a launch direction while Stasis is active |
| 1, 2, or 3 | Choose an upgrade after clearing a level |
| R | Restart the current level |

### Features

- **Physics-based movement:** The ball keeps its momentum and slows gradually through friction.
- **Stasis ability:** Pause the ball and charge a directional launch.
- **Endless levels:** The game begins with 15 designed levels. After those, it generates new obstacle layouts.
- **Moving obstacles:** Some walls and hazards move back and forth, adding timing challenges.
- **Upgrade choices:** Clear a level to choose one of three randomly selected upgrades.
- **Visual effects:** Includes a subtle ball trail, particles, a pulsing goal, and screen shake on impacts.

### Upgrades

Upgrades improve different parts of the ball and its Stasis ability. Examples include:

- Longer Stasis duration and shorter cooldowns
- Stronger launches and higher maximum speed
- Better momentum retention
- Improved control over spin
- A larger goal capture radius

The available choices are randomized after each level, so each run can develop differently.

### How the Code Works

The game is contained in a single HTML file. You do not need separate CSS or JavaScript files.

- **HTML** creates the page, game canvas, and control instructions.
- **CSS** styles the page and canvas.
- **JavaScript** runs the game.
- **Canvas drawing** displays the ball, walls, hazards, goal, upgrade screen, and visual effects.
- **Physics and collision logic** update the ball's movement and detect contact with walls, hazards, and the goal.
- **Stasis logic** pauses movement and converts keyboard input into launch force.
- **Level generation** creates additional obstacle layouts after the 15 designed levels.
- **Game loop** repeatedly updates the game and redraws the canvas.

## Running the Game

1. Keep `stasis-ball-prototype.html` on your computer.
2. Open the file in a modern web browser.
3. Enjoy!

## Credits

Created by **Aaqib Mohammed** and **Olaf Rozner** for **Hack Club Haven**.
