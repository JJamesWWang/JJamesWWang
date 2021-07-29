---
title: Telekinetic Dodgeball
isfeatured: true
preview: /assets/images/telekinetic-dodgeball-preview.gif
video: https://youtube.com/embed/6A7LHCtfCes
description: Multiplayer first-person shooter dodgeball game
date: 2021-07-23
tags:
- Unreal Engine 4
- PC
extra_tags:
- Multiplayer
- FPS
- Team-Based
- 3D
- Physics
- C++
- Blueprints
- Gameplay Ability System
- Online Subsystem Interface
- Visual Studio
- Perforce
- Solo
- Sophomore Summer
---

Telekinetic Dodgeball is a competitive multiplayer first-person shooter based around the game of dodgeball. It features a lobby system based around the Steam subsystem plugin provided by Unreal Engine 4 to connect players wishing to compete with each other.

## Responsibilities
***

* Programming and blueprinting the entire game, which includes:
	1. Adopting the Gameplay Ability System for client-side prediction of game mechanics.
	2. Extending UE4's Character class to add new types of movement, networking included.
	3. Ensuring proper replication of the Game State across clients and to the UI.
	4. Working with UE4's Online Subsystem Interface in order to create a lobby system that allows for multiplayer play.
	5. Setting up physics, collision, and extending UE4's Projectile Movement Component to implement desired dodgeball mechanics.
* Building on top of several free content assets for level editing and UI design when working from scratch would have been too troublesome.
* Finding and editing sound effect assets and distinguishing between when sounds should be played locally or replicated.

## Development
***

Development of Telekinetic Dodgeball began in late May 2021 through prototyping an earlier version of the game called Backfire. Because the next university semester would begin at the start of September, the scope of the game was kept relatively small, with aims to finish the game by the end of July. Unreal Engine 4 was chosen as the game engine because of its built-in multiplayer capabilities, but also for learning purposes. The game's main mechanics and gameplay systems were finished early July, and overall polishing (UI, art assets, sound effects) was added in afterwards. Telekinetic Dodgeball was released on July 23rd on Itch.io, a week before its intended deadline.

## Points of Interest
***

### Game State

The game state of Telekinetic Dodgeball is similar to several other competitive games; it's a system where matches consist of rounds. Each round is played out until a certain criteria is met and then the next round begins, continuing until the time runs out. If there's a tie and a winner can't be determined, then the game goes into overtime. I decided to map this out on Figma because it's difficult to keep the entire state machine in my head, so here is the diagram I made.

![Telekinetic Dodgeball Game State Deterministic Finite Automata](/assets/images/td-game-state-dfa.png)


### Other
* The Itch.io page can be found [here.](https://jjameswwang.itch.io/telekinetic-dodgeball)
* Perforce was used as the version control software as opposed to Git; however, the source code of the complete game can be found [here.](https://github.com/JJamesWWang/Telekinetic-Dodgeball)