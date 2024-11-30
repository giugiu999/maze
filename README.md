# maze

## Features
1. **Maze Generation**
   - Uses **Depth-First Search (DFS)** to generate the maze.
   - Randomly selects an unvisited neighboring cell, breaks the wall in between, and continues until all cells are visited.

2. **Maze Solving**
   - Uses **Breadth-First Search (BFS)** to find the shortest path from the start to the end.
   - Stores the path in a `path` variable and returns it upon reaching the endpoint.

3. **Visualization**
   - Prints the maze in the command line:
     - Walls are represented by `█`.
     - Open paths are represented by spaces.
     - Solved path is represented by `•`.

## Output
Run the program to automatically generate a random maze, find the solution path, and print both the maze and the solution.



