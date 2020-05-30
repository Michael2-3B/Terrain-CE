# Terrain-CE
Terrain CE is currently a TI-Basic experiment of mine in generating a height map and representing it like terrain in an isometric view.

Download here: https://github.com/Michael2-3B/Terrain-CE/raw/master/TERRAIN.8xp

Examples:

![Isometric Beach Terrain](https://raw.githubusercontent.com/Michael2-3B/Terrain-CE/master/screenshots/beach.png)

![Isometric Pyramid Terrain](https://raw.githubusercontent.com/Michael2-3B/Terrain-CE/master/screenshots/pyramid.png)

The generator algorithm works by providing height values in a matrix that are no more than 1 higher or lower than the neighboring nodes.
The smoothing code afterwards removes one block dips and spikes.

There is also now a map editor in the program to make a custom heightmap! Check it out:

![Height Map Editor](https://raw.githubusercontent.com/Michael2-3B/Terrain-CE/master/screenshots/mapeditor.png)

If you want, you can try out the pyramid map by downloading [[B].8xm](https://raw.githubusercontent.com/Michael2-3B/Terrain-CE/master/[B].8xm), and then make sure to store it into matrix [A] when you want to use it.

Forum Thread:
https://www.cemetech.net/forum/viewtopic.php?p=285909#285909
