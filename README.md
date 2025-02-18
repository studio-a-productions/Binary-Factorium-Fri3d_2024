# Binary Factorium - Fri3d_2024
An open-source 2D game in the making with C++, vs code, platform.io, my "blood, sweat and tears", for the Fri3d Camp badge 2024

## Info
**Binary Factorium** is an game in development for the Fri3d Badge 2024 inspired by automation/factory building games and a more recent youtuber who created a automation game for the *Pico 8*.

Binary Factorium is set in a post-space-war timeline in a binary star system, where you, a random employee of MegaCorp have been given control of a drone to create factories in said star system. Be aware though, hostile worlds wait upon you.

## Performance and Design problems

**Please note that there are problems and flaws in this project:** 
- Binary Factorium is a *side project* and being developed by a single programmer with limited experience in Arduino libraries.
- World Generation is my goal, with hopefully a big enough map on each planet to please most gamers.
- There are performance limitations to consider, GPU, Storage and Memory.
- Having a lot of dynamic parts (conveyors or pipes) might lead to worse performance, even after optimizations.
- Pixel art is the style of the game for obvious reasons.

## Solutions
When I find solutions myself or they were suggested and will be used in the game, they'll be displayed below.

### Outpost Shield Capacitator (GPU planet deload)
The Outpost Shield Capacitator (or OSC) is a building/facility that shares your storage and productions with planets (when any input or output conveyors are connected). Or in simple terms: it stores the production rate of your outpost and stops simulating the planet when you are not on it. Which means all grids not connected will not produce anything when you are on another planet.


---

## Want to help?
All support is welcome! Right now, I'm not sure if the project will count as an modified os or something like that. I tried looking at the documentation for the vs code platform.io, but the details are limited. 
Any and all suggestions are welcome, found some flaws or potential bugs? --> let me know!
