# cemelife1.github.io
# Dodge The Creeps - Custom Modifications

This project is based on the **Dodge the Creeps** tutorial from the Godot game engine. The game has been customized to include the following features and enhancements as part of a school assignment.

## Modifications:

1. **Health System:**
   - The player now has **3 health points**. Every time the player is hit by an enemy, they lose 1 health point. When health reaches zero, the game ends.
   - A visual health display (such as hearts or a health bar) could be added to represent the player's health, but it is currently printed in the game console.

2. **Invincibility Frames (iFrames):**
   - After the player is hit, they gain temporary **invincibility** for 1 second to prevent consecutive hits from enemies.
   - This allows the player to have a brief period of safety to recover or reposition themselves.

3. **Improved Collision Handling:**
   - Collision handling has been adjusted to ensure that the player does not get hit repeatedly when invincible. Messages are displayed in the console to indicate when the player is hit, is invincible, and when invincibility wears off.

4. **Game Over Trigger:**
   - The game now properly triggers a **Game Over** screen when the player's health reaches zero. Previously, the game would end after the first hit. This was fixed by adding a health check to ensure that the game only ends when the player's health is fully depleted.

## How to Play:
- Use the arrow keys to move your character.
- Avoid the enemies (creeps) that spawn on the screen.
- Survive as long as possible to achieve a high score. Keep an eye on your health and make use of the invincibility after each hit!

## Play the Game:
You can play the modified version of Dodge the Creeps [here](https://cemelife1.github.io/mygame/Dodge%20The%20Creeps.html).

## Author:
- Chiagozie Emelife
