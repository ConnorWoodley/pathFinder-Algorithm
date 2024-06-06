# pathFinder-Algorithm
A simplified version of a path finding algorithm.

Initially this project started out of motivation to create a 3d game, in which an enemy would roam around the map searching for the player. I struggled creating a system to find the player for this AI, so I seperate dfrom the project and focused on pathfinding to understand the intricacies of the algorithm. I started around the 15th of May, at which time I understood the size of the project. While do-able, it would lead me to think of programming in a different perspective than I had before. I viewed coding as a gateway to create games, simple fun nonsense that was stimulating in the moment. However, upon finishing this project, i've develouped a new taste for code, simulations. This aquired taste originally bagan began when I created the, somewhat buggy, preditor vs prey simulation. I loved that project, and spent a majority of my time working on the different nuances of the simulation. Of course, most of my projects would do as simple screensavers, but none the less I take pleasure in the creativity the derives from it.

The pathFinder can be maipulated through the following inputs and values.
mapSize; The amount of cells in the map, this can be increased to however large the user desires. It's recommended to keep the size above 20 due to the speed of the pathFinder, as well as some noticable bugs.
cellSize; The size of the cells in the map, the larger the cellSize; the clearer the map. it's recommended to keep it's value above 1.
wallValue; While the program automatically updates the wallValue in order to increase or decrease the difficulty as needed, the value can be manipulated by the UP and DOWN arrow keys as well as 'q' on the keyboard. UP arrow increases the wallValue, making open areas change into walls, DOWN arrow does the opposite. 'q' on the keyboard shuts down the automatic updates, making the number of walls stay consistant.
'e' on the keyboard will pause the program, making it light up in a rainbow! for fun obviously.

There are still bugs in the code, its gaurenteed, seeing as i'm still relatively new to coding. Though, I wish to gain more experience and discover more about coding as a profession.
