# alien_invasion
A space invaders like game built on python with pygame. The goal of the game is to control a small ship that fires bullets and defeat the wave of invading aliens before they invade earth. 

Player starts the game with the play button. The green alien ships will move to the right of the screen. When the aliens hit the right
side of the screen, they will drop down one level and travel to the left. The aliens bounce back and forth, lowering each time, until they reach the bottom of the screen or strike the ship.

The player controls a ship that moves left and right and fires a maximum of 3 bullets (on the screen at one time). The bullets travel upwards and make the alien ships dissapear when a collision is detected. Each destroyed ship gives the player a set number of points. 

Each time the player completes a wave of aliens, a new wave of aliens appears. This new wave moves quicker and awards the player more points per destroyed alien.

If the aliens reach the bottom of the screen or strike the player controlled ship, a life is lost and the current wave resets. When all lives are lost, the player loses.

The game tracks the player score, level they are on, number of lives, and always displays the high score in the middle of the screen. High score stays updated as long as player plays game until the end of the game and does not exit the pygame window. 

Player can restart game with the play button when all lives are lost. Player can use "q" button to exit the game. 
