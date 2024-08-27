## Squirrel Eat Squirrel

#### Overview:

Squirrel Eat Squirrel is a fun and engaging 2D game developed using Python's Pygame library. The objective of the game is to control a squirrel, eat smaller squirrels, grow larger, and avoid getting eaten by larger squirrels.
## Table of Content 

- Features
- Installation
- How to Play
- Game Controls
- Game Structure
- Customization
- Acknowledgments
## Features

- Simple yet addictive gameplay: Control a squirrel, eat others, and grow in size.
- Randomly generated environment: Grass and squirrels are randomly placed and move independently.
- Win and lose conditions: Grow large enough to win or lose if you run out of health.
- Health system: The player starts with 3 health points and loses one each time hit by a larger squirrel.
- Dynamic camera system: The camera follows the player squirrel with a slight delay, giving a sense of movement.
## Installation

1. #### Clone the repository:

git clone https://github.com/kunal-1207/Squirrel Eat Squirrel.git

cd Squirrel Eat Squirrel

2. #### Install the required dependencies:


Ensure you have Python 3.x and Pygame installed. If not, you can install Pygame using pip:
pip install pygame


3. #### Run the game:

Navigate to the project directory and run:

python squirrel_eat_squirrel.py

    
## How To Play 

- Control the squirrel to eat smaller squirrels and grow in size.
- Avoid larger squirrels as they will damage your squirrel.
- The game ends when you either reach a specific size (win condition) or lose all your health (lose condition).
## Game Controls

- Arrow keys (or WASD): Move the squirrel.
- 'r' Key: Restart the game after winning or losing.
- 'ESC' Key: Quit the game.
## Game Structure

 #### Player
- The player controls a squirrel that can move in four directions.
- The squirrel can bounce, giving a dynamic movement effect.
- The player's health decreases when hit by a larger squirrel and increases in size when consuming a smaller squirrel.

 #### Enemy Squirrels
- Enemy squirrels are randomly placed in the game world.
- They move in random directions and bounce as well.
- If they collide with the player, the outcome depends on their size compared to the player.

 #### Grass
- The grass objects provide a background for the game world.
- They are randomly placed and do not interact with the player or enemy squirrels.
## Customization

You can customize various game parameters in the code:

-  #### Player & Enemy Attributes:

- 'STARTSIZE': Initial size of the player's squirrel.
- 'MOVERATE': Speed of the player's squirrel.
- 'SQUIRRELMINSPEED', 'SQUIRRELMAXSPEED': Speed range for enemy squirrels.

-  #### Game Settings:

- 'FPS': Frames per second.

- 'NUMGRASS', 'NUMSQUIRRELS': Number of grass objects and enemy squirrels.

-  #### Graphics & Sounds:

Update the image and sound file paths in the 'main()' function.
## Acknowledgements

This game was developed using the Pygame library. Special thanks to the Pygame community for their tutorials and documentation.


