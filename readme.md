RedBlock.js - Classic Version

Description:
RedBlock.js is a simple 2D game engine for JavaScript projects. It is ideal for platformer games with physics, camera movement, and health system. It is currently under development and intended for quick tests and prototypes.

How to use:
1. Include the redblock.js file in your HTML:
   <script src="redblock.js"></script>

2. Use the following functions in your script:

   createPlayer(x, y)         - Creates the player at a specific position
   health(min, max)           - Sets minimum and maximum health (in developed)
   addPlatform(x, y, w, h)    - Adds a platform at a given position and size
   startGame()                - Starts the game loop

Important:
- Always call startGame() after setting up the player and platforms.
- Calling startGame() too early may result in missing elements or logic errors.

Default controls:
- W / Up Arrow / Space: Jump
- A / Left Arrow: Move left
- D / Right Arrow: Move right

Recommended structure:
MyGame/
├── index.html
├── redblock.js
└── blockbar.css

Future versions:
You will be able to use redblock(2), redblock("arcade"), or redblock("editor") to choose different styles or behaviors.

Author:
Created by Lucas for educational and experimental purposes.
