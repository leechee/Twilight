# Twilight - A 2D Platformer Inspired by Hollow Knight

Twilight is a 2D platformer built using Unreal Engine 5. Taking visual and gameplay inspiration from titles like Hollow Knight, this project focuses on delivering satisfying movement mechanics, challenging enemy AI, fluid animations, and an immersive atmosphere. From knockback systems to parallax-scrolling tilesets, Twilight is built with attention to detail through solo development.


https://github.com/user-attachments/assets/573e6739-7398-468a-9f81-dc9730447c8d

---

## Features

### Implemented
- Smooth 2D platformer movement with Hollow Knight-style camera tracking
- Player abilities: dash, sword throw, and double jump
- AI enemies with stun, attack, and charge behaviors
- Health and damage systems with knockback mechanics
- Animated death and stun sequences
- Custom maps with parallax backgrounds
- Particle effects and ambient lighting
- Modular animation system with hitbox integration
- Sound effects synchronized to animations

### Planned
- NPC interaction systems and in-game shop
- Minecraft-style pixel text rendering
- Save and load functionality

---

## Setup Instructions

### Requirements
- Unreal Engine 5
- Git

### Installing Unreal Engine 5

1. Download the [Epic Games Launcher](https://www.unrealengine.com/en-US/download)
2. Install the launcher and create an Epic Games account
3. Open the launcher and install Unreal Engine 5 from the "Unreal Engine" tab

### Cloning and Running the Project

```bash
git clone https://github.com/leechee/Twilight.git
cd Twilight
```

1. Launch Unreal Engine 5
2. Select "Open Project" and navigate to the `Twilight.uproject` file
3. Wait for assets and shaders to compile

---

## Development Roadmap

- [ ] Learn Aseprite for pixel animation workflow
- [ ] Implement jump delay for improved feel
- [ ] Add heart-based health system UI
- [ ] Create in-game Minecraft-style text rendering
- [ ] Implement NPC interaction and shop systems
- [ ] Update ball chain enemy death sprite (remove sparks)

---

## Development Log

<details>
<summary><strong>View complete development timeline</strong></summary>

### October 2023
**10/4/2023**
- Learned sprite animation implementation from Itch.io resources
- Implemented basic movement controls (jump, dash, move)
- Configured default input bindings and Pawn Controller

**10/5/2023**
- Created initial map using imported tilesets
- Implemented parallax background using 3D layering technique
- Added attack animation with input binding
- Matched camera settings to Hollow Knight specifications

**10/6/2023**
- Added sound effects for attack and jump actions
- Updated sprite masking and lighting systems
- Initial project push to GitHub

**10/7 - 10/8/2023**
- Implemented attack hitbox with hit registration system
- Added stunned state on enemy hit
- Expanded map layout and fixed collision issues
- Created enemy idle animation for BallChain enemy type

**10/9 - 10/10/2023**
- Synchronized repository for remote development
- Added stun animation with sound effect
- Enabled multi-hit registration in warrior Blueprint

**10/13/2023**
- Implemented warrior death animation
- Added health and damage systems
- Removed collision on death
- Fixed turn-around hit detection bug

**10/17 - 10/21/2023**
- Resolved parallax rendering bug with enemy corpses
- Implemented AI enemy player tracking with navmesh
- Fixed enemy falling through ground issue
- Adjusted navmesh agent height parameters

**10/25 - 10/26/2023**
- Implemented knockback system using forward vectors

**10/29 - 11/1/2023**
- Constrained AI enemy movement to Y axis
- Implemented AI attack behaviors
- Started development of enemy charge state

### December 2023
**12/16 - 12/18/2023**
- Fixed lighting system and finalized dash implementation
- Enabled dash to phase through enemies
- Polished dash animation and sound effects
- Implemented enemy despawn after 5 seconds post-death
- Fixed player input handling after death

**12/19 - 12/21/2023**
- Improved dash mechanics with edge case velocity fixes
- Added snow particle effects
- Updated charge animation logic
- Fixed multiple attack bugs and stun state issues
- Restricted jumping to grounded state only
- Rebuilt navmesh for dynamic runtime generation

**12/22 - 12/24/2023**
- Expanded level design
- Added non-collidable decorative tiles
- Reduced player walk speed for better game feel

### 2024
**1/7/2024**
- Disabled Lumen for performance optimization
- Adjusted shadow tile rendering
- Increased frame rate, adjusted spawn translation

**3/10/2024**
- Project paused for other commitments

**5/18/2024**
- Fixed floating character bug
- Changed camera to orthographic projection
- Resolved screen tearing and tile shifting issues
- Known issues: sprite lighting bleed and wave tile glitch when jumping

</details>

---

## Project Structure

```
Twilight/
├── Config/           # Engine and game configuration files
├── Content/          # Game assets and blueprints
│   ├── Audio/        # Sound effects and music
│   ├── Maps/         # Level maps
│   ├── Characters/   # Character blueprints and animations
│   ├── Animations/   # Animation sequences
│   ├── Tilesets/     # Sprite tiles and backgrounds
│   └── Blueprints/   # Game logic blueprints
└── Twilight.uproject # Unreal Engine project file
```

---

## About

Solo development project by Jason Lee. Built using Unreal Engine 5 with the goal of recreating the tight mechanics and atmospheric ambiance of games like Hollow Knight in a 2D pixel art platformer.

---

## Contributing

This is a solo development project, but contributions are welcome. Feel free to fork the repository, submit issues, or propose improvements, particularly for AI behaviors and visual polish.

---

## License

This project is for educational and portfolio purposes. Please contact the developer before reusing assets or substantial portions of the codebase.
