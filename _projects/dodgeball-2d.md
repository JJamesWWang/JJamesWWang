---
title: Dodgeball 2D
isfeatured: true
preview: /assets/images/dodgeball-2d-preview.gif
video: https://youtu.be/VaIP5w-9UTc
description: Multiplayer 2D dodgeball game
date: 2021-01-05
tags:
- Unity
- PC
extra_tags:
- Multiplayer
- Team-Based
- 2D
- Physics
- C#
- Mirror
- GitHub
- Visual Studio Code
- Solo
- Sophomore Winter
---
Dodgeball 2D is a competitive top-down arena dodgeball game with RTS-style movement.

## Responsibilities
***

* Programming the entire game, which includes:
	1. Using Mirror's NetworkManager to accept player connection requests to form lobbies and teams.
	2. Granting players client-side prediction on the power of their dodgeball throw despite throwing being server-authoritative.
	3. Validating players' movement commands using 2D vector math.
	4. Allowing players to set their own name that all other players will see.
	5. Writing a custom script that automatically sets the bounds of the dodgeball arena; any modification of the arena's size will shift the bounds accordingly.

## Development
***

Development of Dodgeball-2D began in mid December 2020 after I completed a Udemy course involving the use of the multiplayer framework Mirror. The game was intended to be a small project to demonstrate my understanding of multiplayer programming in Unity with Mirror. The project was released for testing on January 3rd; it was playable but riddled with bugs with many issues related to networking. I ended up stumbling upon this [GitHub issue](https://github.com/vis2k/Mirror/issues/1940), which was still open at the time, that was causing a bug in my code. It was then I decided I would try Unreal Engine 4 in search of a game engine with better built-in multiplayer capabilities. The long gap between this project and Telekinetic Dodgeball was spent learning UE4.

## Points of Interest
***

* The Itch.io page can be found [here.](https://jjameswwang.itch.io/dodgeball)
* The GitHub repository can be found [here.](https://github.com/JJamesWWang/Dodgeball-2D)