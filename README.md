# GameOfLife
## (CURRENT STABLE VERSION: 3.0)

This is my "Game Of Life Simulator" - based on conway's game of life
implemented using Java, the graphical framework "Processing 3" and the library "ControlP5"!

Hope you have fun creating some nice worlds!

(Screenshots will follow.)

Some fonts may be not correctly shown.
I'm aware of that "system-based bug" and will fix it soon.


---------


### "What do I need to run it?"
- You need "Java" installed on your computer.

### "How can I start it, its no ".exe"-file?"
- If you have "Java" installed, simply double click the ".jar"-file.
- You can also open the console and type "java -jar <filename>.jar" to get debug information.


---------


## Features:

INFO: Use "R" to return to main screen.

### - Simulator
 - simulate a random or user generated world
 - press "P" to pause and continue a simulation

### - World Builder
 - build a own world to run a simulation on
 - use "left mousebutton" to draw living cells
 - use "right mousebutton" to remove living cells
 - use "C" to clear the current world


---------


## Version Infos:

### Version 1:
- working simulation using random seeds or seeds set by user

### Version 2:
- added world editor (you can now load your own worlds, no longer random generated only)

### Version 3:
- fixed: drawing bug (simulation is faster now)
- fixed: drawing bug for world builder (fast drawing)
- added: hold and drag mouse to draw or remove cells using the world builder
- added: possibility to stop simulation (using "P")
- added: showing simulation steps and population in window title
- added: showing if a simulation finished and stop calculating (less cpu usage for same simulation)


---------


## Planned:
- saving and loading worlds
- extended user tools for world editor