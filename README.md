﻿# Golf Game Name

by Team Name: Square Cubed

## Pitch
Top-down golf game with enemy NPCs scattered throughout each level. The player has to hit their ball around these enemies in order to complete each level. Different enemies will have different effects when they touch the ball, such as resetting level progress, adding a stroke, or decreasing the distance the ball can travel.

## Setting
The golf courses could take place in multiple settings depending on the current level. For example: 
<br/> 

**Level 1:** Classic Green Course <br/>
A traditional, golf course with lush green grass, rolling hills, and water hazards.

**Level 2:** Desert Dunes <br/> 
A dry, sun-scorched desert with rolling sand dunes, cacti, and rocky outcrops.

**Level 3:** Snowy Peaks <br/>
A winter environment high in the mountains, covered in snow and ice.

**Level 4:** Volcanic Inferno <br/>
A golf course built around an active volcano, with lava rivers, and rocky cliffs.

## Game Components

### Objects

- Golf Ball (Player-Controlled)
- Direction Indicator
- Enemies (AI-Controlled Objects)
- Power-Ups
- Terrain Types – Different surfaces that affect ball movement.
- Goal (Hole)
- Wind Zone 
- GUI Elements:
    - Swing Power Meter
    - Angle Indicator
    - Stroke Counter
    - Wind Direction & Speed Display
    - Power-Up Display
### Attributes

- Golf Ball:
    - Position (X, Y)
    - Velocity (speed and direction)
    - Current terrain type
    - Current status (normal, airborne, slowed, etc.)
    - Active power-ups
- Enemies:
    - Position (X, Y)
    - Movement pattern (Patrolling, Chasing, etc.)
    - Special effect on ball (Knockback, Gravity, Instant Reset)
- Power-Ups:
    - Position (X, Y)
    - Effect duration
    - Type (Shield, Speed Boost, etc.)
- Terrain:
    - Type (Grass, Ice, Sand, etc.)
    - Friction value
    - Speed modifier
- Wind Zone:
    - Wind strength
    - Wind direction

---

### Relationships & Game Logic

- Player controls the ball using a pull-back and release mechanic. The further the drag, the stronger the shot.
- Angle modifier allows fine-tuning of shot direction. The player adjusts the aim before release using keyboard or mouse scroll.
- Wind modifies the ball’s movement when airborne. The ball's trajectory changes depending on wind strength and direction.
- Different terrains affect ball speed and control.
	- Grass: Standard speed and control.
	- Sand & Snow: Significantly slows the ball.
	- Ice: Causes the ball to slide, reducing control.
	- Lava River & Water: Resets the ball.
	- Rocky Surface: Low friction, allowing extended movement.
- Enemies interfere with the ball’s movement.
    - Patroller – Moves in a circular path or follows a set route.
	- Obliterator – Resets the ball to the starting point if touched.
	- Bouncer – Knocks the ball in a random direction on impact.
	- Gravity Zone – Pulls the ball toward the enemy, with a much stronger effect when the ball is in the air.
	- Anchor Ball – Increases gravity on the ball, preventing it from being launched into the air.
	- Chaser – Actively chases the ball when it comes close. If it catches the ball, the level resets.
- Power-ups temporarily boost the player’s ability.
	- Shields - Protects the ball from enemy effects for a limited time.
	- Speed Boost - increase the ball speed for the next swing, allow to travel faster
	- Better Aiming - Shows the projectile til the ball stop moving after swing.
	- Time slow - Slow down time and make it easier to aim and avoid enemy
- The game is won when the ball lands in the hole in the fewest strokes possible.
## Game mechanics
### Ball Mechanism
#### Player Control
- The player controls the golf ball using a pull-back and release mechanic. To aim, they click and drag in the opposite direction of the desired shot.
- An angle modifier allows fine-tuning of the shot direction using either the keyboard or the mouse scroll wheel before release.
    - Adjusting the angle can enable the ball to travel through the air, avoiding terrain friction.
    - (Optional) A wind modifier affects the ball’s trajectory, adding an extra challenge. The wind direction and intensity influence the ball's movement, especially when airborne.
- When the player releases the mouse button, a force proportional to the drag distance is applied to the ball.
#### Ball Movement
The ball's friction and speed vary depending on the terrain:
- Grass: Standard speed and control.
- Sand & Snow: Significantly slows the ball.
- Ice: Causes the ball to slide, reducing control.
- Lava River & Water: Resets the ball.
- Rocky Surface: Low friction, allowing extended movement.

### Enemy Mechansim 
Different enemies are placed around the level. Each enemy has a special ability to prevent the player to reach the hole.

Patroller – Moves in a circular path or follows a set route.
Obliterator – Resets the ball to the starting point if touched.
Bouncer – Knocks the ball in a random direction on impact.
Gravity Zone – Pulls the ball toward the enemy, with a much stronger effect when the ball is in the air.
Anchor Ball – Increases gravity on the ball, preventing it from being launched into the air.
Chaser – Actively chases the ball when it comes close. If it catches the ball, the level resets.

### Level Power-Ups
Shields - Protects the ball from enemy effects for a limited time.
Speed Boost - increase the ball speed for the next swing, allow to travel faster
Better Aiming - Shows the projectile til the ball stop moving after swing.
Time slow - Slow down time and make it easier to aim and avoid enemy

### Goal
The game is won by navigate around enemies and hazards, and hitting the ball into designated holes in the game level in as few strokes as possible. 

### Game mechanics Paragraph Version
The game revolves around a pull-back and release mechanic for controlling the golf ball. Players click and drag in the opposite direction of their desired shot to aim, with an angle modifier allowing fine-tuning of the shot direction using the keyboard or mouse scroll wheel. This adjustment can enable the ball to travel through the air, bypassing terrain friction, while an optional wind modifier adds an extra layer of challenge by influencing the ball’s trajectory, especially when airborne. Upon releasing the mouse button, a force proportional to the drag distance is applied to the ball, propelling it forward. The ball’s movement is affected by terrain-specific friction and speed: grass offers standard control, sand and snow slow the ball significantly, ice causes sliding and reduced control, lava rivers and water reset the ball, and rocky surfaces allow for extended movement due to low friction. Scattered throughout each level are enemies designed to hinder progress. Patrollers move in circular paths or set routes, Obliterators reset the ball to the starting point upon contact, Bouncers knock the ball in random directions, Gravity Zones pull the ball toward them (with stronger effects when the ball is airborne), Anchor Balls increase gravity to prevent aerial shots, and Chasers actively pursue the ball, resetting the level if they catch it. To counter these challenges, players can collect power-ups like Shields to protect against enemy effects, Speed Boosts to increase ball speed for the next swing, Better Aiming to visualize the ball’s trajectory, and Time Slow to make aiming and avoiding enemies easier. The goal is to navigate around enemies and hazards, using strategic shots and power-ups to hit the ball into designated holes in as few strokes as possible. Each level presents unique terrain, enemy placements, and environmental challenges, requiring players to adapt their strategies to succeed.

## Team Members
David Wei <br/>
Erik Ignacio <br/> 
Kenneth Wang <br/>

## Division of Labor

### David Wei: <br/>
Placeholder

### Erik Ignacio: <br/> 
Placeholder

### Kenneth Wang: <br/>
Placeholder

## Prototype Screenshot
