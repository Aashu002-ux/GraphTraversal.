# GraphTraversal.

Description:
This Python program generates a random N×N grid with obstacles and allows the user to specify source and goal positions. It uses Depth-First Search (DFS) to find a path from the source to the goal while avoiding obstacles. The program then outputs the path found (if any), along with the order in which nodes were visited during the DFS traversal.

Key Features:
Random Grid Generation: The grid is generated randomly with obstacles (#), and the grid cells are empty (.).
DFS Pathfinding: The program finds a path from a specified source to a goal using DFS, while avoiding obstacles.
Topological Order: The order in which nodes are visited during the DFS traversal is printed.
Source and Goal Input: The user can specify the source and goal positions. The program ensures that neither the source nor the goal is placed on an obstacle.
