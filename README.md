# ActionPlatFormer

## Project Overview

ActionPlatFormer is a 3D action-platformer game developed using **Unreal Engine 5 and Blueprint Visual Scripting**. The game combines 3D environments with 2D pixel-art characters, creating a unique visual style.

Players navigate challenging parkour-style levels, fight enemies, collect power-ups, activate checkpoints, and face a powerful boss with a large amount of health.

The game also features background music, sound effects, and combat mechanics that require players to carefully time their attacks and movements while managing limited health.

## Main Goal

The goal of this project was to create an interactive action-platformer while gaining hands-on experience with game development using Unreal Engine 5.

I focused on implementing gameplay mechanics through Blueprint Visual Scripting, designing challenging levels, and integrating combat, movement, checkpoints, power-ups, and audio systems into a playable experience.

## Download & Play (Windows)

**You can play ActionPlatFormer without installing Unreal Engine 5.**

### Step 1: Download the Game

1. Visit the [ActionPlatFormer Latest Release](https://github.com/cjsantizo/UnrealEngine-ActionPlatFormerGame1/releases/latest).
2. Scroll down to the **Assets** section.
3. Download `ActionPlatFormer - Windows Release.zip`.
4. Extract the ZIP file to your computer.

### Step 2: Launch the Game

1. Open the extracted folder.
2. Locate `ActionPlatFormer.exe`.
3. Double-click the executable to launch the game.
4. Navigate the parkour environments, defeat enemies, collect power-ups, and challenge the boss.

**Important:** Keep all the extracted files and folders together. The game requires its packaged assets and Unreal Engine runtime files to function properly.

## Features

- **3D Platforming:** Navigate challenging parkour-style levels with obstacles and platforms.
- **2D Pixel-Art Characters:** Combines 2D pixelated characters with 3D environments.
- **Enemy Combat:** Fight enemies that require multiple attacks to defeat.
- **Boss Battle:** Face a powerful boss with significantly higher health than regular enemies.
- **Power-Ups:** Collect abilities and power-ups to assist during gameplay.
- **Checkpoint System:** Activate checkpoints as you progress through levels.
- **Player Health System:** Survive encounters with a limited amount of health.
- **Music and Sound Effects:** Includes background music and sound effects to enhance the gameplay experience.
- **Blueprint Visual Scripting:** Gameplay systems and interactions are implemented using Unreal Engine Blueprints.

## Technologies Used

- **Game Engine:** Unreal Engine 5
- **Visual Scripting:** Blueprint Visual Scripting
- **Development Environment:** Unreal Editor
- **Platform:** Windows
- **Game Type:** 3D Action Platformer with 2D Characters

## How to Open the Project in Unreal Engine 5

For developers or recruiters interested in exploring the game's implementation, the complete Unreal Engine project is available in this repository.

### Requirements

- Unreal Engine 5 (a compatible version)
- Epic Games Launcher
- Git (optional)

### Step 1: Download the Source Project

Clone the repository using Git:

```bash
git clone https://github.com/cjsantizo/UnrealEngine-ActionPlatFormerGame1.git
```

Alternatively:

1. Click the green **Code** button at the top of this repository.
2. Select **Download ZIP**.
3. Extract the downloaded project folder.

### Step 2: Open in Unreal Engine

1. Open the downloaded project folder.
2. Locate `ActionPlatFormer.uproject`.
3. Double-click the file to launch Unreal Engine 5.
4. Allow the engine to load the project assets and compile any necessary shaders.

### Step 3: Run the Game

1. Once Unreal Editor opens, load the main level `MAP_LVL` if it is not already selected.
2. Click the **Play** button in the editor toolbar.
3. The game will launch inside Unreal Editor.
4. Explore the environment and test the gameplay mechanics.

### Step 4: Explore the Blueprints

Developers can navigate through the project's `Content` folder to examine its Blueprint implementations.

Some of the project's Blueprints include:

- `BP_ActionChar` — Player character
- `BP_shark` — Shark enemy
- `BP_captain` — Captain character
- `BP_AbilitiesPickUp` — Ability pickups
- `BP_Spawner` — Spawning system
- `GM_Action` — Game mode

These Blueprints provide insight into the game's implementation and how different gameplay systems interact.

## Project Structure

```text
ActionPlatFormer/
├── Config/                    # Project configurations
├── Content/                   # Game assets, levels, and Blueprints
├── .gitattributes
├── .gitignore
├── ActionPlatFormer.uproject   # Unreal Engine project file
└── README.md                  # Project documentation
```

The standalone Windows game is available separately under **GitHub Releases**.

## What I Learned

Through this project, I gained practical experience developing an interactive game using Unreal Engine 5 and Blueprint Visual Scripting.

I strengthened my understanding of gameplay logic, character movement, enemy behavior, player health, checkpoint systems, level design, and integrating audio into a game.

This project also helped me understand how different gameplay mechanics work together to create a complete player experience, from navigating levels and defeating enemies to collecting power-ups and facing a final boss.
