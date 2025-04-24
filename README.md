
# 🌒 Twilight - A 2D Platformer Inspired by Hollow Knight

Twilight is a handcrafted 2D platformer built using Unreal Engine 5. Taking visual and gameplay inspiration from titles like *Hollow Knight*, this project focuses on delivering satisfying movement, challenging enemies, fluid animation, and an immersive atmosphere. From knockback systems to parallax-scrolling tilesets, Twilight is built with meticulous attention to detail and driven by solo development.

---

## 🕹 Game Features (Planned & Implemented)

- Smooth 2D platformer movement
- Hollow Knight-style camera tracking
- Dash, sword throw, and double jump abilities
- AI enemies with stun, attack, and charge behaviors
- Health and damage systems with knockback
- Animated death and stun sequences
- Custom maps and parallax backgrounds
- Particle effects and ambient lighting
- NPC interactions and in-game shop (planned)
- Minecraft-style pixel text rendering (planned)
- Modular animation system with hitboxes
- Sound effects synced to animations
- Save/load system (planned)

---

## 🔧 How to Set Up the Project

### Requirements
- **Unreal Engine 5**
- **Git** (to clone the repository)

### Download Unreal Engine 5
You can download and install Unreal Engine 5 from the [Epic Games Launcher](https://www.unrealengine.com/en-US/download). 

1. Go to the [Unreal Engine download page](https://www.unrealengine.com/en-US/download).
2. Click on “Download Now” to get the Epic Games Launcher.
3. Install the launcher and create an Epic Games account if you don’t have one.
4. Open the launcher and install Unreal Engine 5 under the “Unreal Engine” tab.

---

### Cloning the Repository

```bash
git clone https://github.com/your-username/twilight-platformer.git
cd twilight-platformer
```

---

### Opening the Project

1. Launch Unreal Engine 5.
2. Click on "Open Project" and navigate to the `.uproject` file inside the cloned folder.
3. Open and wait for assets and shaders to compile.

---

## ✅ To-do List

- [ ] Learn Aseprite for pixel animation
- [ ] Hollow Knight-style camera movement
- [ ] Implement jump delay
- [ ] Add heart-based health system
- [ ] Create in-game Minecraft-style text
- [ ] Add NPC interaction and shop systems
- [ ] Abilities: dash, sword throw, double jump
- [ ] Update ball chain enemy death sprite (no sparks)

---

## 📓 Devlog

<details>
<summary><strong>Click to expand full devlog</strong></summary>

### 10/4/2023
- Learned sprite animations from Itch.io
- Basic movement controls (jump, dash, move)
- Set default controls and Pawn Controller

### 10/5/2023
- Created map using imported tilesets
- Parallax background using 3D layering
- Attack animation added and bound to input
- Matched camera settings to Hollow Knight

### 10/6/2023
- Added SFX to attack and jump
- Updated sprite masking and lighting
- Pushed initial project to GitHub

### 10/7 - 10/8/2023
- Implemented attack hitbox and hit registration
- Stunned state on hit
- Expanded map and fixed collision
- Created enemy idle animation (BallChain)

### 10/9 - 10/10/2023
- Synced repo for remote work
- Added stun animation and sound
- Enabled multi-hit registration in warrior Blueprint

### 10/13/2023
- Added warrior death animation
- Implemented health and damage systems
- Removed collision post-death
- Fixed turn-around hit detection bug

### 10/17 - 10/21/2023
- Fixed parallax bug with enemy corpses
- AI enemy follows player; navmesh issues fixed
- Resolved issue with enemy falling through ground
- Adjusted navmesh agent height

### 10/25 - 10/26/2023
- Added knockback using forward vectors

### 10/29 - 11/1/2023
- AI enemy constrained to Y axis
- AI attacks implemented
- Started implementing enemy charge state

### 12/16 - 12/18/2023
- Fixed lighting and implemented dash
- Dash goes through enemies
- Cleaned up dash animation and SFX
- Enemies despawn after 5 seconds dead
- Fixed player input after death

### 12/19 - 12/21/2023
- Dash improvements: fixed edge case velocities
- Added snow particle effects
- Charge animation logic updated
- Fixed multiple attack bugs and stun states
- Jumping locked to grounded state
- Rebuilt navmesh for dynamic runtime

### 12/22 - 12/24/2023
- Level design expansion
- Added non-collidable decorative tiles
- Nerfed walk speed

### 1/7/2024
- Disabled Lumen, adjusted shadow tiles
- Increased FPS, adjusted spawn translation

### 3/10/2024
- Paused project for new work

### 5/18/2024
- Fixed floating character bug
- Changed camera to orthographic
- Fixed screen tearing and tile shifting
- TODO: resolve sprite lighting bleed and wave tile glitch when jumping

</details>

---

## 📁 Project Structure (Partial)

```
twilight-platformer/
│
├── Assets/
├── Maps/
├── Blueprints/
├── Characters/
├── Animations/
├── Tilesets/
├── Sounds/
├── twilight.uproject
```

---

## 🎮 About the Developer

Solo dev project by Jason Lee. Built using Unreal Engine 5 with the goal of recreating the tight mechanics and ambiance of games like *Hollow Knight* in a side-scrolling pixel world.

---

## ⭐️ Contributions

This is a solo development project but feel free to fork, star, or raise issues! Improvements, especially for AI behaviors and visual polish, are welcome.

---

## 📜 License

This project is for educational and portfolio purposes. Please contact the developer before reusing assets or major portions of the codebase.
