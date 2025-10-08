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