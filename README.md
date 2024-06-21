# A((star)-Path-Finding
We will be building a path finding visualizer tool to visualize the a star pathfinding algorithm as it runs. This astar pathfinding algorithm is an informed search algorithm which means it is much more efficient that your standard algorithms like breadth first search or depth first search.

Highlights:


Implementation of a Class to Visualize Grid and Obstacles 🟦

Created a Spot class to represent each grid cell with methods for setting states like start, end, barrier, and path.
Setting Up Nodes with Different Colors 🎨

Utilized a color scheme to differentiate between start nodes, end nodes, barriers, and paths for better visualization.
Handling Mouse Clicks to Set Start, End, and Barriers ⌨️

Enabled interactive setting of start, end, and barrier nodes through mouse clicks.
Starting Pathfinding Algorithm with Space Key Press ⏯️

Initiated the A* pathfinding algorithm with the press of the space key.
Algorithm Finds Shortest Path by Considering All Possible Nodes 🛤️

Implemented an A* algorithm that efficiently explores all potential nodes to determine the shortest path.
Reconstructing Path by Tracing Back from End to Start Node 🔍

Added functionality to trace back and visually highlight the shortest path from end to start node once found.
Ability to Reset Program by Pressing 'C' to Clear Screen ♻️

Provided a convenient way to reset the grid and start over by pressing the 'C' key.



Key Insights:



Clear Representation of the Grid and Obstacles 🧩

The visualization tool offers a clear and intuitive representation of the grid and obstacles, making the pathfinding process easier to understand.
Efficient Shortest Pathfinding 🚀

The A* algorithm effectively finds the shortest path by exploring and updating all potential nodes' distances.
Convenient Reset Functionality 🔄

The ability to reset the program provides users with an easy way to restart or modify the grid setup as needed.

IMAGE-1: Defining Starting point with orange color and Ending point blue color

![Screenshot 2024-06-21 232547](https://github.com/ankur182/A-star--Path-Finding/assets/98750453/e01acaba-a82b-4949-8ca2-b1b69947aace)
IMAGE2: The visualizer will display the shorted path from purple color 

![Screenshot 2024-06-21 232736](https://github.com/ankur182/A-star--Path-Finding/assets/98750453/01b43c50-f821-40fe-b238-10e2dd885a93)

IMAGE3: (Its worst case) When there is no path possible then it path visualizer will go into infinite loop

![Screenshot 2024-06-21 232819](https://github.com/ankur182/A-star--Path-Finding/assets/98750453/5a1ca949-9d41-4ee0-923a-7980b27584ce)
