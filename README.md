# Pac-Man-GBA
This implementation of Pᗣᗧ•••MᗣN is written in C and designed to be emulated on the Nintendo Game Boy Advance (GBA) video game console.
The code follows the design pattern of Apple Frameworks.

## About
+ Because this implementation of Pac-Man was created for a Computer Science class at GT, I am unable to post the C code associated with the game.
+ However, the game can be played on a Game Boy Advance emulator on Linux or Ubuntu using the files in this repository. See the "How To Make & Play" section below.
+ Each C file in the game's source code is named after a standard Apple framework, along with one Foundation.h header file. Each C file named after an Apple framework aims to serve the purpose of that framework. For example, my Metal.c file provides a low-overhead graphics rendering engine for the game using Direct Memory Access (DMA) and primitive drawing functions.
+ Apple frameworks used in the design of Pac-Man:

  Core Foundation
  
  Core Graphics
  
  Foundation
  
  Game Controller
  
  Image IO
  
  Metal
  
  Quartz Core
  
  Text Kit
  
  UIKit


# How To Make & Play
1. Ensure that you are running Linux or Ubuntu; the emulator is designed to be run only on Linux or Ubuntu.
2. Install the Game Boy Advance emulator and necessary tools from the command line:

   `sudo   apt-get   install   gcc-arm-none-eabi`
   
   `sudo   apt-get   install   libnewlib-arm-none-eabi`
   
   `sudo   apt-get   install   cs2110-vbam-sdl`
   
3. Download the files from this repository (including the res folder) into one directory.
4. At this directory, from the command line, run:

   `make vba`


## About Pac-Man

GAMEPLAY
+ Guide Pac-Man through the maze in this arcade-style game as you help him to
  eat all of the Pac-Dots.
+ In order to win the level, you must consume all of the Pac-Dots.

CONTROLS
+ Begin playing Pac-Man at any time by pressing the ENTER key.
+ Reset the game to the start screen at any time by pressing the BACKSPACE key.
+ Use the UP, DOWN, LEFT, and RIGHT arrows to change Pac-Man's direction as you
  navigate through the maze.
+ Pac-Man continues moving in his current direction until you change it. He will
  collide with walls stop moving until you tell him how to turn.
