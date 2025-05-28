# programming2

This repository contains my “Programmazione 2” course final project.

## Overview

The final assignment for the course required students to design a Python project in pairs. Together with my teammate, we created a **local multiplayer game** called **Hunter and Prey**, developed using **Python** and **Pygame**. The game features real-time mechanics, role switching, and a best-of-three structure that keeps the gameplay competitive and engaging.

## Contents

  * `main.py` – Entry point of the game, manages game loop and state transitions (rounds, showdown).
  * `player.py` – Defines the `Player` class with movement logic, roles, and health/score tracking.
  * `projectile.py` – Manages projectile behavior and collision detection.
  * `settings.py` – Stores all game configuration values (screen size, speeds, colors, etc.).
  * `graphic.py` – Handles drawing, UI updates, and rendering text/images to the screen.
  * `assets.py` – Loads and organizes fonts, sounds, and image resources.

* 📁 **`fonts/`** – Custom fonts used for titles, score display, and in-game text.

* 📁 **`images/`** – Game sprites and backgrounds, including:

  * Hunter and prey characters
  * Background image

* 📁 **`sounds/`** – Audio assets including:

  * Background music (theme)
  * Sound effects like projectile fire and impact

## Game Description

**Hunter and Prey** is a 2-player competitive game featuring the following phases:

1. **Round 1** – One player is the hunter, the other is the prey. The hunter tries to catch or shoot the prey.
2. **Round 2** – Roles are reversed.
3. **Showdown** – If neither player dominates in the first two rounds, both become **hunters** and fight until one is defeated.

Each player controls their character via keyboard inputs (different key bindings), and the match rewards reflexes, strategy, and accuracy. The game includes:

* Collision logic
* Scoring system
* Role switching
* Health and projectile systems
* Dynamic sound and music playback

## Purpose

This project showcases our understanding of:

* **Python OOP** and modular design
* **Pygame** for 2D game development
* Event handling and real-time input
* Game architecture and resource management
