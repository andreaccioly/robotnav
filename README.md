# RobotNav
Implementation of A* Algorithm to find the shortest path from a start node and a end node aronud polygons.
The robot has to navigate its way around obstacles. Given a set of convex polygons in a plane that represent the obstacles, the robot has to find the shortest path around the polygons from a specified start point to a desired end point.
Input:
Each problem instance (file) is specified in a separate text file in the following format:
Line 1 - Contains the x and y coordinates of the start point
Line 2 - Contains the x and y coordinates of the end point
Line 3 - Number of convex polygons in the scene
Line 4 to N - 
  First number number of vertices in polygon i
  N pairs of numbers representing the x and y vertices of polygon i in order
