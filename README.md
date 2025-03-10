# Golf Game Name

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
- Terrain Types – Different surfaces that affect ball movement.
- Goal (Hole)
- (Optional) Wind Zone 
- (Optional) Power-Ups
- GUI Elements:
    - Swing Power Meter
    - Angle Indicator
    - Stroke Counter
    - (Optional) Wind Direction & Speed Display
    - Power-Up Display
### Attributes

- Golf Ball:
    - Position (X, Y)
    - Velocity (speed and direction)
    - Current terrain type
    - Current status (normal, airborne, slowed, etc.)
    - (Optional) Active power-ups
- Enemies:
    - Position (X, Y)
    - Movement pattern (Patrolling, Chasing, etc.)
    - Special effect on ball (Knockback, Instant Reset)
- (Optional) Power-Ups:
    - Position (X, Y)
    - Effect duration
    - Type (Shield, Speed Boost, etc.)
- Terrain:
    - Type (Grass, Ice, Sand, etc.)
    - Friction value
    - Speed modifier
- (Optional) Wind Zone:
    - Wind strength
    - Wind direction

---

### Relationships & Game Logic

- Player controls the ball using a pull-back and release mechanic. The further the drag, the stronger the shot.
- Wind modifies the ball’s movement when airborne. The ball's trajectory changes depending on wind strength and direction.
- Different terrains affect ball speed and control.
	- Grass: Standard speed and control.
	- Sand & Snow: Significantly slows the ball.
	- Ice: Causes the ball to slide, reducing control.
	- Lava River & Water: Resets the ball.
	- Rocky Surface: Low friction, allowing extended movement.
- Enemies interfere with the ball’s movement.
	- Patroller – Moves in a circular path or follows a set route.
	- Chaser – Actively chases the ball when it comes close. If it catches the ball, the level resets.
- Enemy Modifier: 
	- Obliterator – Resets the ball to the starting point if touched.
	- Bouncer – Knocks the ball in a random direction on impact.
- (Optional) Power-ups temporarily boost the player’s ability.
	- Shields - Protects the ball from enemy effects for a limited time.
	- Speed Boost - increase the ball speed for the next swing, allow to travel faster
	- Better Aiming - Shows the projectile til the ball stop moving after swing.
	- Time slow - Slow down time and make it easier to aim and avoid enemy
- The game is won when the ball lands in the hole in the fewest strokes possible.
## Game mechanics
### Ball Mechanism
#### Player Control
- The player controls the golf ball using a pull-back and release mechanic. To aim, they click and drag in the opposite direction of the desired shot.
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

Enemy type:
- Patroller – Moves in a circular path or follows a set route.
- Chaser – Actively chases the ball when it comes close. If it catches the ball, the level resets.
Modifier: 
- Obliterator – Resets the ball to the starting point if touched.
- Bouncer – Knocks the ball in a random direction on impact.
### (Optional) Level Power-Ups
- Shields - Protects the ball from enemy effects for a limited time.
- Time slow - Slow down time and make it easier to aim and avoid enemy
- Speed Boost - increase the ball speed for the next swing, allow to travel faster
- Better Aiming - Shows the projectile til the ball stop moving after swing.
### Goal
The game is won by navigate around enemies and hazards, and hitting the ball into designated holes in the game level in as few strokes as possible. 

### Paragraph Version
The player controls the golf ball using a pull-back and release mechanic, aiming by clicking and dragging in the opposite direction of the desired shot. When released, a force proportional to the drag distance is applied to the ball. Optionally, a wind modifier can influence the ball’s trajectory, with wind direction and intensity affecting movement, especially when airborne. The ball interacts with various terrains, each impacting friction and speed: grass provides standard movement, sand and snow significantly slow the ball, ice reduces control due to sliding, rocky surfaces have low friction, allowing extended movement, while lava rivers and water reset the ball.

Throughout the level, enemies hinder the player's progress toward the hole. Patrollers move in set patterns, while Chasers actively pursue the ball and reset the level upon contact. Some enemies have modifiers that further impact gameplay; for example, Obliterators reset the ball to the starting position upon contact, while Bouncers deflect it in a random direction. To counter these obstacles, players can collect power-ups if functionality is added, such as Shields, which temporarily protect the ball from enemy effects, Time Slow, which slows time for better aiming and enemy avoidance, Speed Boost, which increases ball speed for the next shot, and Better Aiming, which provides a trajectory preview until the ball stops moving.

The objective is to skillfully navigate around enemies and hazards, strategically utilizing mechanics and power-ups to land the ball in designated holes in as few strokes as possible.
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
