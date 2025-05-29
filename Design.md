# Cart Designs
This document contains a list of "pseudo game design documents" that help
outline a game's focus and design.

### Table of Contents
1. [GeoBattle](#1.-GeoBattle)

# 1. GeoBattle
Cart: [geo.p8](geo.p8)
Release: [https://aethari.itch.io/geobattle](https://aethari.itch.io/geobattle)

## Game Summary
The player spawns in an arena. After a few seconds, a boss appears and
begins to fight the player. The boss has a variety of attacks, and a
health bar. The player can attack the boss by spawning friendly blue
cubes, which deal damage when they collide with the boss. Once the player 
defeats the boss (or dies), they get a score based on their performance.
Then the player earns XP based on their score. After the fight is over, 
the player can spend XP on a variety of stat upgrades to help their fight.
Each upgrade goes up in cost when bought. After upgrading (or not), the 
player can fight the boss again.

### Stats
Here is the list of stats that can be improved, plus what they do:
| Stat name     | Function                    				|
|---------------|-------------------------------------------|
| Health        | The player's HP             				|
| Mana			| The player's mana							|
| Speed         | The player's movement speed 				|
| Friends		| The # of friendly cubes the player spawns |
| Damage		| The amount of damage a friendly cube does |

## Inpsirations
- Undertale
- Nodebuster

## Genre(s)
Incremental, survival

## Gameplay
The player controls a single sprite character, which uses "real"
physics to move, meaning that they take a split second after pressing
a movement key to reach max speed. The player's character has an 
amount of HP directly relating to their health stat. If the player's
health reaches 0, they die.

### Mechanics
- Movement: Do I even need to tell you what this is?
- Invincibility: The player can cast an invincibility spell at the
				 cost of mana, which regens over time
- Spawning: Every 10 seconds, the player spanws friendly blue cubes
			that do damage to the boss when they collide with it
- XP: I told you about XP in the game summary

## Art
The game's base color palette is a 1-bit black and white. While
the game will generally follow this rule, exceptions can be made
(especially for the UI).

### Design
The game's art will take a minimalistic design, with most sprites 
consisting of outlines with no fill.
