Pathfinding Algorithms: Dijkstra and A*
This repository contains implementations of popular pathfinding algorithms, including Dijkstra's Algorithm and A (A-Star) Algorithm*. These algorithms are used to find the shortest path between two points on a grid, taking into account possible obstacles.

Features
Interactive Interface: You can set custom start and end points for the pathfinding process.
Visualization: The algorithms are visualized in real-time on a grid, showing the exploration of nodes.
Obstacle Support: You can draw walls or obstacles on the grid, and the algorithms will find paths around them.
Multiple Algorithms: Compare the performance of Dijkstra’s Algorithm and A* Algorithm on the same grid.
Algorithms
Dijkstra's Algorithm
Dijkstra's algorithm finds the shortest path between a starting node and all other nodes in a weighted graph. It explores all possible paths, ensuring that the shortest path is always found.

A* Algorithm
A* is an optimized version of Dijkstra's algorithm that uses heuristics to speed up the process. A* prioritizes nodes that are closer to the goal, making it faster in most cases.

How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/pathfinding-algorithms.git
Install the required dependencies:

bash
Copy code
pip install pygame
Run the Python script to start the visualization:

bash
Copy code
python pathfinding_visualizer.py
Usage
Left Click: Place the start point, end point, or obstacles on the grid.
Right Click: Remove obstacles from the grid.
Enter: Start the pathfinding process.
Esc: Reset the grid.
Screenshots

Technologies
Python
Pygame for visualization
License
This project is licensed under the MIT License. See the LICENSE file for more details.
