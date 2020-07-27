



![N|Solid](https://github.com/SFTtech/openage/raw/master/assets/logo/banner.png)

This document will serve as a record of the planned trajectory of the project, the successes along that path, and the steps that have yet to be reached.
It is based on the unformated openage/doc/milestones.md

# Milestones - a roadmap

# Part One - Basic functions and singleplayer
- [x] 0. Decide on the technology architecture
    - [X] Language
    - [X] Libraries
    - [X] Coding Standards
- [x] 1. Having a running application list syntax required (any unordered or ordered list supported)
    - [X] Fullscreen
    - [X] Launches to game with no outside console commands
    - [X] Menu may not be present
- [x] 2. Rendering a single building
    - [X] University
    - [X] Reads info in from stock AOE2 files
       -   [X] Internal only
       -   [X] This must be changed for all outward-facing releases
- [x] 3. Rendering the map
    - [X] Diamond shaped
    - [X] Monoterrain
    - [X] Arbitrary number of buildings
    - [X] Scrolling
       -   [X] Traditional keyboard controls
       -   [X] Modern mouse/keyboard combination controls
- [x] 4. Rendering characters on the map
   -   [X] Animated
- [x] 5. Mouse use
     - [X] Select characters
     - [X] Select buildings
     - [X] Basic commands
	     - [X] "Go here"
	     - [X] "Delete"
- [x] 6. NPC movement
	- [x] Pathfinding
	- [x] Collision detection
- [x] 7. HUD - Basics
	- [x] Units
	- [x]  Buildings
	- [x]  Supports
- [ ] 8. HUD - Research
    -   [ ] Explorable research tree implemented
    -   [ ] Ability to engage in research is added to HUD
- [x] 9. Creation/Building
	- [x]  Ability to create villagers
	- [x]  Ability to build buildings
- [x] 10. Implement resources
	- [x] Trees, food, stone, gold
	- [x] Creation/building is now associated with resource costs
- [x] 11. HUD - Resources
	- [x] Resource values are added to HUD 12. resource gathering by villagers
- [x] 12. Character specifications
	- [x] Health points implemented
	- [x] Damage modifiers implemented
	- [x] Unit colors implemented
- [ ] 13. Terrain altitutdes implemented
	- [ ] Effects on character movement
	- [ ] Effects on ballistic range
	- [ ] Effects on ballistic attack
- [ ] 14. Working singleplayer
	- [ ] AI

# Part Two - Multiplayer and distribution
- [ ] 15. Dedicated server implementation 
	- [ ] User actions are mapped to physic frame ids
	- [ ] Physic frame ids are synced up
- [ ] 16. Basic multiplayer support
	- [ ] Two networks
	- [ ] Share one map (grassland)
	- [ ] One villager per player
	- [ ] Battles can be fought
	- [ ] Bugs are to be expected
- [ ] 17. "Finished" program
	- [ ] All other steps completed
	- [ ] Network bugs resolved

# Part Three- Long-Term Plans
- [ ] 18. Game recording / playback
- [ ] 19. Lobby/ server implementation
- [ ] 20. AI Python API (GlaDOS?)
- [ ] 21. Messages and taunts 
- [ ] 22. Client-side prediction in multiplayer
- [ ] 23. Random map generation (RMS scripts?)
- [ ] 24. AOE2 map reader
-   -   [ ] Scenario reader
-   -   [ ] singleplayer campaigns?

# Remember Our Project Goals
-  Performance
	- Responsiveness
	- FPS
	- Required resources
- Cloning AOE2
	- As exact as possible
	- Fully authentic look and feel
- High-quality code
	- Concise
	- Reusable
	- Well-documented

# Part Four - Supported games

- [X] Age of Empires 2
    -   [ ] CD version (The Conqueror's)
    -   [ ] HD Edition
    -   [ ] Definitive Edition
- [X] Age of Empires 1
    -   [ ] CD version (Rise of Rome)
    -   [ ] Definitive Edition
- [X] Star Wars: Galactic Battlegrounds
    -   [ ] CD version (Clone Campaigns)

# Don't Panic!
