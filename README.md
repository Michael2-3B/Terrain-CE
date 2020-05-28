# Terrain-CE
Terrain CE is currently a TI-Basic experiment of mine in generating a height map and representing it like terrain in an isometric view.

Download here: https://github.com/Michael2-3B/Terrain-CE/raw/master/TERRAIN.8xg
(You will get a GENERATE.8xp file and a DISPLAY.8xp file, which must be run in that order; unless you have a 16x16 matrix in [A] already generated.)

Examples:

![Isometric Beach Terrain](https://raw.githubusercontent.com/Michael2-3B/Terrain-CE/master/screenshots/beach.png)

![Isometric Pyramid Terrain](https://raw.githubusercontent.com/Michael2-3B/Terrain-CE/master/screenshots/pyramid.png)

The generator algorithm works by providing height values in a matrix that are no more than 1 higher or lower than the neighboring nodes.
The smoothing code afterwards removes one block dips and spikes.

Also note, when prompted for a seed in GENERATE.8xp, you may enter any real value, or type 0 to use a random seed.

Forum Thread:
https://www.cemetech.net/forum/viewtopic.php?p=285909#285909
