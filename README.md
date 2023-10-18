# Introduction

After playing video games all my life and being inspired by devlogs on YouTube, I decided to seriously try out game dev for the first time. One of my favorite games is Hollow Knight, so for my first project, my goal is to make a basic 2D action adventure utilizing PaperZD in Unreal Engine 5.

## Overall To-do List

- [ ] Learn Aesprite so I can blend animations so only the above half sprite performs the animation attack override <br>
- [ ] Have camera movement similar to Hollow Knight <br>
- [ ] Make movement mechanics more similar to the Hollow Knight (e.g. dashes) <br>
- [ ] Add jump delay <br>
- [ ] Make a basic enemy programmed by simple AI <br>
- [ ] Able to fall through platforms after pressing down <br>
- [ ] Add health bar (or hearts) system
- [ ] Add Minecraft text in-game
- [ ] Interactions with NPCs and a shop system
- [ ] Inventory system
- [ ] Apply knockback

## Devlog

#### 10/4/2023

- [X] Learned how to create character animations using sprites from Itch.io.<br>
- [X] Used Blueprint to code basic movement controls for the warrior<br>
- [X] Added a jump, forward, and backward<br>
- [X] Added a dash that increases runPlayRate and movement speed<br>
- [X] Inputted default control settings and Pawn Control<br>

#### 10/5/2023
- [X] Added a custom created basic map using imported sprites and tilesets<br>
- [X] Utilized 3D functions to create a parallax effect in the background of the game<br>
- [X] Added an attack animation override so the warrior has an attack animation<br>
- [X] Researched camera movement from Hollow Knight and reset default inputs to match Hollow Knight<br>

#### 10/6/2023
- [X] Added SFX to attack and jump animations<br>
- [X] Set all sprite masking to DefaultUnlit to create lighting<br>
- [X] Added lighting throughout the map using point and directional lighting<br>
- [X] Learned git and github basics and pushed this project into the cloud <br>
- [X] So far, the game has a twilight feel, so I named the game Twilight (tentative) <br>

#### 10/7/2023
- [X] Added attack animation delay <br>
- [X] Added hitbox for attack animation<br>

#### 10/8/2023
- [X] Added hiting registration for attack animation <br>
- [X] Added get hit registration for attack animation with a stunned state <br>
- [X] Made the map more expansive (always improving)<br>
- [X] Fixed collision box for platforms <br>
- [X] Created idle animation for the first enemy, BallChain <br>
- [X] Improved README to be more organized and include devlog <br>

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