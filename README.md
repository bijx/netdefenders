# NetDefenders

A game built using Unity in C#. Protect your top level website domain from online attackers in a survival styled FPS game.

![Banner](https://imgur.com/hoZ3giX.jpg)

## Installation

Clone to desktop or download zip. Make sure data folder is in the same directory as the executable. When the Unity configuration window appears, select preferred settings and press "Play!".

## Gameplay

When presented with the main menu, you can either press play to jump right into the game, or edit your skill tree. If it is your first time playing, the game will prompt you to enter a username. NetDefenders follows a similar control scheme to most PC FPS games plus a few changes, with the controls defined below:

```
# Locomotion
W - Forward
S - Backward
A - Strafe Left
D - Strafe Right 
LShift - Sprint
Space - Jump

# Interaction
LClick - Shoot
R - Reload
E - Melee
X - Use Repurposer
G - Throw Grenade

# Location Specific
F - Hold while looking at cash box to carry
T - Repair turret when looking at it
1 - Buy health (when in base)
2 - Buy ammo (when in base)
3 - Buy grenades (when in base)
```



## Game Details
### Basics
The basic purpose of the game is to defend your base aura from the enemy bugs by eliminating them. They appear in waves, and their numbers grow each attack! Bits are the in game currency you receive from destroying bugs and picking up cash boxes. Your health can be replenished, but the base's cannot. The game ends when either you or your base aura is destroyed.

### Weapons
Your primary weapon is the Decompiler Mk.II which has ammo, firerate, and damage upgrades available in the skill shop. You can also use your melee, however it is far less effective especially against a large number of enemies. Grenades work fantastic against hordes of enemies in higher levels, but can also kill you if you get too close! 

You also have your trusty Repurposer—a hacking tool that rewrites the source code of the bugs attacking you and forces them to target their fellow bugs! Useful when you jump into a crowd of foes, however it has a rather slow recharge rate.

### Cash Boxes & Powerups
Randomly upon destroying a bug, either powerups or cash boxes can drop. Powerups can give short boosts such as infinite ammo and fast fire rates. 

Cash boxes are green cubes that the enemies drop upon destruction. Each is worth 100 bits if you return it to your base's aura. To pick up a cube, hold F when looking at it. It is possible to carry more than one, however it may glitch the pickups and you may get stuck holding onto them.

## Bugs
Currently there are several bugs that I will hopefully fix in future updates (if there are even future updates).

- Quit button in main menu doesn't work, you need to Alt-F4.
- At the end of a game, the mouse disappears in the Game Over menu. To fix, Alt-Tab out of game and then Alt-Tab back into the game.
- If your total ammo is below 15 and you reload, you lose whatever you had in your current magazine.
- Sometimes the on screen button hints (i.e. "Hold F to pickup.") remain on the screen. They should go away eventually on their own.