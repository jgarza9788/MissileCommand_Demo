RedRain
-------------------------------------
[Asset Store Link](http://u3d.as/CLj)  
© 2017 Justin Garza

PLEASE LEAVE A REVIEW OR RATE THE PACKAGE IF YOU FIND IT USEFUL!
Enjoy! :)

Contact  
-------------------------------------
Questions, suggestions, help needed?  
Contact me at:  
Email: jgarza9788@gmail.com  
Cell: 1-818-251-0647  
Contact Info: [justingarza.net/contact](http://justingarza.net/contact/)
  
Description/Features
-------------------------------------
A redesigned version of a classic game* One handed Gameplay
* Save HighScore
* Optimized for mobile
* Fully commented C# code

Terms of Use
-------------------------------------
You are free to add this asset to any game you’d like
However:  
please put my name in the credits, or in the special thanks section. :)  
please do not re-distribute.  

Table of Contents 
-------------------------------------
1. How to Play
2. Scripts

  
How to Play
-------------------------------------
1. Hit Play Button  
![Imgur](http://i.imgur.com/xVlCi9Gl.png)

2. Drag your finger on the bottom part of the screen to move the cursor/crosshairs.  
![Imgur](http://i.imgur.com/e0Sfc0hl.png)

3. Double tap to shoot!  
![Imgur](http://i.imgur.com/Ikv0BBPl.png)


Scripts 
-------------------------------------
This section will be a list of the scripts and a breif description of what they do, but for more information please see the comments in the scripts and/or each out to me. 

**AudioManager.cs**  
A central gameobject to handle audio.

**Base.cs**  
This script that handles the 3 bases in the game.
Also manages ammo in each base.
Inherits from Location.cs

**CameraBounds.cs**  
Sets bounds to determine what is in the camera's view.

**Canvas.cs**  
Just used to reference the GameManager.cs and set the state to play again.

**City.cs**  
The script that handles the 6 Cities in the game.
Inherits from Location.cs.

**Constants.cs**  
Variables and methods that can be used in other scripts.  

**Cursor.cs**  
This is the Cursor or the CrossHair in the game.

**EnemyProjectile.cs**  
This script controls the EnemyProjectile.
Also controls when these enemyProjectiles split.
Inherits from Projectile.

**EnemyProjectileSpawner.cs**
This Script spawns enemyProjectiles.
Controls number of projectiles,speed, and the split frequency, and split possibility.
Increments projectile variables to make the game harder for each wave.

**Explosion.cs**  
This script controls the explosions that occur, when a missile blows up, a missile splits, or a location is hit.
Gen (short for generation counts the chain reactions of explosions), more points are provided based on this value.
If explosion has a trigger collider the explosion will interact with projectiles.

**GameManager.cs**  
This script serves as a center of control for the game.
States of the this script determines the state of the canvas.

**Location.cs**  
This is the parent class (base class for City and Base).

**ObjectPool.cs**  
A pool of objects that can be reused.
See PoolManager.cs for more details.

**PlayerProjectile.cs**  
Used to control the player's projectile.
Inherts from projectile.

**Points.cs**
Used to control the points during the current game.

**PoolManager.cs**  
This script manages pools of objects.
Spawning and Recycling is used instead of creating and destorying since it uses less resources.

**Projectile.cs**  
This is the parent class (base class) for PlayerProjectile and EnemyProjectile.

**RecycleObject.cs**  
Used to recycle objects in the pool manager.

**RowOfObjects.cs**  
Controlls the row of objects (Cities and Bases).

**TouchController.cs**  
Cool little thingie that switches between a playbutton and a touchpanel.






