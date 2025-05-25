# Cart Designs
This document contains a list of "pseudo game design documents" that help
outline a game's focus and design.

### Table of Contents
1. [Untitled soulslike game](#1.-Untitled-soulslike-game)

# 1. Untitled soulslike game
Cart: [souls.p8](souls.p8)

### Name Ideas
- 

## Game Summary
The player spawns in an arena. After a few seconds, a boss appears and
begins to fight the player. The boss has a variety of attacks, and a
health bar. The player can attack the boss by swinging a sword (like a
Zelda game). Once the player defeats the boss (or dies), they get a
score based on their performance. Then the player earns XP based on
their score. XP is persistant across runs, but it lost when the player
dies to a boss. After the fight is over, the player can spend XP on a
variety of stat upgrades to help their fight. Each upgrade goes up in
cost when bought. After upgrading (or not), the player can fight the
boss again. The player will not change the direction they are facing
(up), unless they are rolling.

### Stats
Here is the list of stats that can be improved, plus what they do:
| Stat name     | Function                    |
|---------------|-----------------------------|
| Health        | The player's HP             |
| Speed         | The player's movement speed |

## Inpsiration
- SoulsBorne series
- Zelda series
- Undertale
- Nodebuster (for design)

## Genre(s)
Soulslike, rogulike

## Gameplay
The player controls a single sprite character, which uses "real"
physics to move, meaning that they take a split second after pressing
a movement key to reach max speed. The player's character has an 
amount of HP directly relating to their health stat. If the player's
health reaches 0, they die.

### Mechanics
- Movement: Do I even need to tell you what this is?
- Rolling: The player can roll as a supplement for movement, making
		   them invincible for the duration
- Attacking: The player can use the x key to attack, swinging their
			 sword in a wide arc
- XP: I told you about XP in the game summary

## Art
The game's base color palette is a 1-bit black and white. While
the game will generally follow this rule, exceptions can be made
(especially for the UI).

### Design
The game's art will take a minimalistic design, with most sprites 
consisting of outlines with no fill.
