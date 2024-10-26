# Project04-Platformer

# Technically a Platformer
10/26/2024

A 10 second game with basic platformer controlls

## Implementation
Added moving character with sprites for idle, left, and right.
Added tilemap terrain and background.
When pressing E, a bullet will spawn from the player travelling in the most recent direction the player has moved, destroying enemies on contact and destroying itself too. Will automatically destroy itself after 5 seconds or if it hits terrain. The bullet only spawns if the player has a score above 5, and takes 5 away from the total score.
Added Coin Blocks, which switch their sprite renderer to a hit Coin Box on collision and add 5 points to the total score.
Added a flag, which when touched, displays "YOU WIN" on the screen.
Added player HP, which is displayed.
Added score, which is displayed.
Added a homing enemy, which will start tracking you when you get within a certain radius of it. When it touches the player, it will destroy itself and remove 1 from the player HP. On contact with bullet, it is destroyed and 10 points are added to the player score.
When the player reaches 0 hp, their sprite gets deleted and "YOU DIED..." gets displayed on screen.
Added various sound effects.

Camera follows player
WASD-E controls.
Coin Blocks are an interactable object.



## References

Character Controller adapted from Sebastion Lague's Unity 5 Character Controller Tutorials
https://www.youtube.com/playlist?list=PLFt_AvWsXl0f0hqURlhyIoAabKPgRsqjz
https://github.com/SebLague/2DPlatformer-Tutorial

## Future Development
N/A
## Created by
Ethan Brock
