Super Mario Bros Level 1
=============

An attempt to solve the first level of Super Mario Bros using a linear genetric programming algorithm.

![screenshot](https://raw.github.com/justinmeister/Mario-Level-1/master/screenshot.png)

Here I introduce an approach based on Genetic Algorithms (linear genetic programming) to learn the first level from the Mario AI simulator. Each instruction is encoded in a chromosome and after every generation altered by applying crossovers and mutations. During the training phase we concluded that a modification of this approach is more promising. Thus, we created an algorithm that mutated only instructions after Mario failed in the game and neglected crossovers completely. Doing this we ensured that already made progress in solving the game remains. Here you can find a video
https://youtu.be/il1BNu5ma-U showing one solution that the algorithm converged to.

DEPENDENCIES:

Pygame 1.9.1 (Python 2)

Pygame 1.9.2 (Python 3) - a little trickier to get going.

To install dependencies for Python 2.x:

	pip install -r requirements.txt
