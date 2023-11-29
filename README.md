## Overall To-do List

- [ ] Learn Aesprite to blend animations; only the top half of the sprite performs the animation attack override 
- [ ] Have camera movement similar to Hollow Knight
- [ ] Make movement mechanics more similar to the Hollow Knight (e.g. dashes)
- [ ] Add jump delay 
- [ ] Add health bar (or hearts) system
- [ ] Add Minecraft text in-game
- [ ] Interactions with NPCs and a shop system
- [ ] brainstorm shop items and upgrades
- [ ] edit ball chain death sprite to include no sparks
- [ ] destroy actor after delay node

## Devlog

#### 10/4/2023

- [X] Learned how to create character animations using sprites from Itch.io
- [X] Used Blueprint to code basic movement controls for the warrior
- [X] Added a jump, forward, and backward
- [X] Added a dash that increases runPlayRate and movement speed
- [X] Inputted default control settings and Pawn Control

#### 10/5/2023
- [X] Added a custom created basic map using imported sprites and tilesets
- [X] Utilized 3D functions to create a parallax effect in the background of the game
- [X] Added an attack animation override so the warrior has an attack animation
- [X] Researched camera movement from Hollow Knight and reset default inputs to match Hollow Knight

#### 10/6/2023
- [X] Added SFX to attack and jump animations
- [X] Set all sprite masking to DefaultUnlit to create lighting
- [X] Added lighting throughout the map using point and directional lighting
- [X] Learned git and github basics and pushed this project into the cloud
- [X] So far, the game has a twilight feel, so I named the game Twilight (tentative) 

#### 10/7/2023
- [X] Added attack animation delay
- [X] Added hitbox for attack animation

#### 10/8/2023
- [X] Added hiting registration for attack animation
- [X] Added get hit registration for attack animation with a stunned state
- [X] Made the map more expansive (always improving)
- [X] Fixed collision box for platforms 
- [X] Created idle animation for the first enemy, BallChain
- [X] Improved README to be more organized and include devlog

#### 10/9/2023

- [X] Cloned repository to work remotely

#### 10/10/2023

- [X] Added stun animation for the ball chain mob
- [X] Added SFX for the BC_stun
- [X] Added sequence to warrior blueprint to enable multiple hit regis
- [X] Cleaned up some lighting for BC

#### 10/13/2023

- [X] Added death animation for the warrior
- [X] Set health and damage system to the warrior
- [X] Removed collision when dead animation finishes
- [X] Fixed bug where hits would be detected if warrior turned around mid-sequence

#### 10/13/2023

- [X] Added more death charge attack run and charge transition custom animations for ball-chain sprite

#### 10/17/2023
- [X] Fixed bug where enemy bodies would move parallax with the ground
- [X] Programmed enemy AI to follow player at a set speed and acceptable radius
- [X] New bug: navmesh won't work in a 2D space

#### 10/18/2023 
- [X] Fixed navmesh
- [X] Fixed bug where navmesh would not register under tiles
- [X] New bug: ball chain enemy walks through the ground

#### 10/20/2023
- [X] Broke navmesh again...
- [X] Fixed bug where ball chain enemy would walk through the ground

#### 10/21/2023
- [X] Fixed navmesh by lowering agent height in RecastNavMesh-Default item

#### 10/25/2023
- [X] Implemented knockback
- [X] New bug: knockback only works in one direction

#### 10/26/2023
- [X] Knockback works appropriately for any direction using forward vectors

#### 10/29/2023
- [X] Fixed bug where ball chain enemy would still follow player direction when in dead state
- [X] Improved AI targeting fluidity
- [X] Constrained actors to y axis

#### 11/1/2023
- [X] Added attack to the AI
- [X] Multiple bugs with attacking and stun states
- [X] Attempted to implement charge state

#### 11/18/2023
- [X] No changes yet... need to focus on studying for finals
