A* Rover Navigation
-------------

Description
--------
Implementation of the A* search algorithm to navigate a rover across a 10×14 planetary terrain map with variable terrain costs, 8-directional movement, and impassable cells. Supports multiple heuristic strategies for optimal pathfinding.


Features
------
Variable terrain costs: Flat, Rocky, Sand, and Impassable (Cliffs/X)

8-direction movement: N, S, E, W, NE, NW, SE, SW with diagonal cost 1.4

Heuristics:
--------
Manhattan with minimum terrain cost

Scaled Euclidean

Algorithm: A* Search with OPEN (priority queue) and CLOSED lists

Parent tracking for reconstructing the optimal path

Output
--------
For each heuristic, the program prints:

Final path coordinates

Total path cost

Number of nodes expanded

Order of node expansion

g, h, f values along the final path
