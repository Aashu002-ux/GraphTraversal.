# GraphTraversal.

Description:
This Python program generates a random N×N grid with obstacles and allows the user to specify source and goal positions. It uses Depth-First Search (DFS) to find a path from the source to the goal while avoiding obstacles. The program then outputs the path found (if any), along with the order in which nodes were visited during the DFS traversal.

Key Features:
Random Grid Generation: The grid is generated randomly with obstacles (1), and the grid cells are empty (0).
DFS Pathfinding: The program finds a path from a specified source to a goal using DFS, while avoiding obstacles.
Topological Order: The order in which nodes are visited during the DFS traversal is printed.
Source and Goal Input: The user can specify the source and goal positions. The program ensures that neither the source nor the goal is placed on an obstacle.


Usage:

Run the program:After starting the program, it will prompt to input the grid size (N) between 4 and 7.

Input Source and Goal:Once the grid is displayed, the program will prompt to input the source and goal positions. Enter the row and column values for both positions ( 0 0 for the top-left corner).

Program Output: After input the source and goal, the program will:
Display the randomly generated grid.
Display the updated grid with the source (S) and goal (G).
Show the DFS path from the source to the goal (if a path exists).
Display the topological order of the nodes visited during the DFS traversal.

Example:

Enter the size of the grid (between 4 and 7): 5

Enter the source position (row col) between 0 and 4: 0 0

Enter the goal position (row col) between 0 and 4: 4 4

