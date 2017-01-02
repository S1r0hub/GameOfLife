# Game Of Life
## (CURRENT STABLE VERSION: 4)

This is my "Game Of Life Simulator" - based on conway's game of life
implemented using Java, the graphical framework "Processing 3" and the library "ControlP5"!

Hope you have fun creating some nice worlds!

![Main Screen](https://camo.githubusercontent.com/6472520d567879d5483a879c85d526b105979863/687474703a2f2f7369726f2e62706c616365642e6e65742f496d616765732f474f4c2f76332f76335f6d61696e2e6a7067 "Main Screen")<br>
![World Builder](https://camo.githubusercontent.com/ba41e4c19aceaadfb4ac2a3b850eac68f7412abd/687474703a2f2f7369726f2e62706c616365642e6e65742f496d616765732f474f4c2f76332f76335f776f726c642d6275696c6465722e6a7067 "World Builder")<br>
<br>
[>> All Screenshots <<](https://github.com/S1r0hub/GameOfLife/wiki/Screenshots)

<br><br>

Visit my ["Game Of Life wiki"](https://github.com/S1r0hub/GameOfLife/wiki) for more information.

<br><br>
<hr>
<br><br>

### "What do I need to run it?"
- You need ["Java"](https://www.java.com/en/download/) to be installed on your computer.

### WINDOWS: "How can I start it, its no ".exe"-file?"
- If you have "Java" installed, simply double click the ".jar"-file.
- You can also open the console inside the folder you stored the program (SHIFT + RIGHTMB) and type "java -jar filename.jar" to get debug information.

### LINUX: "How can I start it?"
- Open the terminal inside the folder you stored the program and type "java -jar filename.jar".

<br><br>
<hr>
<br><br>

## Features:

INFO: Use "R" to return to main screen.

### - Simulator
 - simulate a random or user generated world
 - press "P" to pause and continue a simulation
   + press [RIGHT ARROW] while paused for next step of simulation

### - World Builder
 - build an own world to run a simulation on
 - use "left mousebutton" to draw living cells
 - use "right mousebutton" to remove living cells
 - use "S" to show toolbar with more options

<br><br>
<hr>
<br><br>

## Version Infos:

### Version 1:
- working simulation using random seeds or seeds set by user

### Version 2:
- added world editor (you can now load your own worlds, no longer random generated only)

### Version 3:
- fixed: drawing bug (simulation is faster now)
- fixed: drawing bug for world builder (fast drawing)
- added: hold and drag mouse to draw or remove cells using the world builder
- added: possibility to pause the simulation (using "P")
- added: possibility to only go one step further using \[RIGHT ARROW\] **while paused**
- added: showing simulation steps and population in window title
- added: showing if a simulation finished and stop calculating (less cpu usage for same simulation)

### Version 4:
- added: resource loader to load fonts and images
- added: application icon
- added: confirm request on exit
- added: showing middle in world builder (light gray cells)
- changed: application fonts
- changed: application window size increased to 1200x600
- fixed: system-based fonts
- world builder: added: gui
- world builder: added: export and import maps as ".golw"-files
- world builder: added: changeable pen size

<br><br>
<hr>
<br><br>

## Planned:
- [X] saving and loading worlds
- [ ] extended user tools for world editor