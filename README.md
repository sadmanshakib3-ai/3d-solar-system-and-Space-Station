Project Title: Hover_Hunt
Project Overview:
"Hover_Hunt" is a 3D action game where the player controls a character in an open 3D space. Flying enemies appear randomly, and the player must survive using movement, guns, and bombs. Power-ups give temporary cheat abilities that enhance gameplay. The game ends when the player’s life reaches zero, and it can be restarted using a key press.

Gameplay Mechanics:
Player Controls:


Movement:


W → Move forward


S → Move backward


A → Rotate left


D → Rotate right


Jump: Character can jump to avoid enemies at specific levels


Shooting:


Left Mouse Button → Fire bullets if a gun is in hand


Camera Controls:


Arrow Keys:


Up → Move camera up


DOWN → Move camera down


LEFT → Rotate camera left


RIGHT → Rotate camera right


Right Mouse Button → Toggle camera mode: first-person/third-person


Enemies:


Type: Round, flying objects


Behavior:


Appear at random vertices in the 3D space


Move towards the player continuously


Animate


The number of enemies is dynamic, not fixed


Power-ups:


Gun: Temporary weapon


Cheat mode activates when picked up


Allows automatic shooting at enemies


Limited time availability


Bomb: Temporary weapon


Clears multiple enemies in range


Limited time availability


Cheat Mode:


Activates only if the player has a gun in hand


Enemies stop moving


Player automatically shoots at enemies in line of sight


The player can still move freely


Deactivates when the gun timer expires


Life and Game Over:


Player life ranges from 100–0


Life decreases when enemies collide with the player


Game ends at life = 0


The player can restart the game using the R key


Restart resets: Life → 100, Score → 0, Power-ups → 0
Game Components:
Player Character:


Constructed using:


Sphere (head)


Cylinders (arms/gun)


Cuboids (body/legs)


Can rotate, move, and jump


Enemies:


Spherical flying objects


Animate continuously


Spawn randomly in the 3D space


Bullets & Bombs:


Bullets → Cuboid shapes moving in gun direction


Bombs → Explosive effect, clearing enemies in a radius


Power-ups:


Appear at random locations for a limited time


The player must collect to activate


Cheat Mode Indicators:


Visual feedback: enemies freeze



Team Work Distribution (3 Members, 4 Functions Each):
Member 1:


Player movement & rotation functions


Jump mechanics


Gun shooting function


Power-up pickup function


Member 2:


Enemy spawn & movement functions


Enemy animation function


Enemy collision detection function


Bullet-enemy interaction function


Member 3:


Bomb power-up & explosion function


Cheat mode activation & auto-shoot function


Camera movement & mode toggle function


Game over & restart function



Game Flow:
Start → Player spawns at center → Enemies spawn randomly


Player moves & collects power-ups


Gun power-up → Cheat mode activates → Enemies stop, auto-shoot


Bomb power-up → Player can clear enemies


Player life decreases on enemy contact


Life reaches 0 → Game over


Press R → Restart → Reset life, score, power-ups


