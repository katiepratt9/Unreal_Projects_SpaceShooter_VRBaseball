# Unreal VR Projects

# VR SpaceShooter
A VR shooting game set in a futuristic robotic lab. Survive waves of enemy robots that continuously spawn and try to eliminate you. 
Use dual pistols or your throwable hammer to fight back.

# Features
- **Health System:** Displays damage taken from enemies, includes health pickups to restore lost health.
- **Combat:**
  - Dual pistols, one in each hand.
  - Throwable hammer that:
    - Kills enemies in one shot and ragdolls them.
    - Breaks statues into pieces when hit.
    - Can be recalled by the player.
- **Enemy AI:**
  - Tracks the player, attacks, and uses run, damage, and death animations.
- **Wave System:**
  - Tracks kill count.
  - Increases difficulty each round.
- **Controls:**
  - Left joystick: Move
  - Right joystick: Rotate
  - Left/Right triggers: Fire respective guns
  - Additional controls: See `/Content/VRTemplate/Input/Actions`
- **Environment:** Built using assets from Quixel Bridge and FAB.

# How to Run
1. Open `UnrealAllProjects.uproject` in the `unreal projects/src/` directory using Unreal Engine.
2. Open the **Content Drawer** at the bottom-left.
3. Navigate to:  
   `Content/Environment Pack 3/Maps/SpaceShooter`
4. Open the map `SpaceShooter`
5. Click **Play** to begin.

# Notes
- Requires a VR headset and controllers.
- A gameplay video(low quality to fit on github) is located in `unreal projects/src/`.
  or watch on youtube: https://www.youtube.com/watch?v=ss342nZ8SaM

# VRBaseball
Simple Baseball VR game where player can pick up a bat(lying to the right of them on a log) and hit endless flying and 
spinning baseball projectiles for points, when the player misses a baseball the points are reset to zero.

#Features 
- colorful assets that make up a backyard from Quixel Bridge and FAB
- Baseball Bat that users can hit baseballs away with to get points 
- Flying baseballs that rotate has they approach the player and fly away when hit with Baseball Bat
- counter for how many baseballs have been hit, resets to 0 when baseball is missed by player(changes from white to red)
- baseball being hit make sound
- pause menu with resume, restart and quit options

# How to Run
1. Open the "UnrealAllProjects.uproject" in the "unreal projects/src" folder in unreal engine.
2. open the content drawer at the bottom left of the screen. 
3. navigate through the folders: content/VRtemplate/maps/VRBaseball
4. double click on VRBaseball and run

# Notes 
- you will need a VR Headset and controllers to play
- a video of the gameplay for VRBaseball is located in the "unreal projects/src" folder
  or watch on youtube: https://www.youtube.com/watch?v=Fr8q7LyTW5A 
