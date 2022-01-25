# PathFinding

**Welcome to Path Visualizer.**
###
This program provides a visual demonstration of the process undergone by Dijkstra and A* (A star)

## Algorithms

It supports the follwing algorithms:

**Dijkstra's Algorithm**: the father of path finding algorithms; guarantees the shortest path
###
Dijkstra's algorithm works by first adding the starting node to a priority queue. It then takes the top node in the priority queue and looks at all of the nodes surrounding it. If the nodes are valid positions then they are added to the priority queue and the top node in the queue is deleted. These nodes that are added to the queue also have a knowledge of what node they were explored from (ie. their parent node) This process is continued until a node is discovered with the same location as the finish node. From that node, a path is created by retracing the steps to the starting node.
###
![dijkstra](https://user-images.githubusercontent.com/36581610/50039437-a6cd8e80-0000-11e9-865a-1c6062046d4f.gif)

**A-Star Algorithm**: arguably the best pathfinding algorithm; uses heuristics to guarantee the shortest path much faster than Dijkstra's Algorithm
###
A* works similarly to dijkstra by creating a priority queue of nodes and then adding new nodes to the queue by exploring the top node on the queue. However in A* the nodes are placed into the queue with a heuristic of distance to the finish node. This means that the node at the top of the queue is always the node closest to the finish node.
###
![astar](https://user-images.githubusercontent.com/36581610/50039438-af25c980-0000-11e9-9fda-f96a2ee6cb2e.gif)

## How to run

To run the file all you need is Java complier running on your device. Use any code editor of your choice i.e. VS Code, Netbeans etc.

1. Open a command prompt window and go to the directory where you saved the java program (PathFinding.java).

2. Type 'javac PathFinding.java' and press enter to compile your code.

3. Now, type 'java PathFinding' to run your program.
