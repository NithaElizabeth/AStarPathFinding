# A* Algorithm for Robot Path Planning

Robots are built to to work under dynamically changing environment or workspace and hence the algorithm or the rules must be devised to ensure an optimistic collision-free path. A* algorithm is a heuristic function based algorithm for optimal path planning. It calculates heuristic function's value at each node on the workspace and checks the adjacent nodes for finding the optimal solution with zero probability of collision.A* is like Greedy Best-First-Search in that it can use a heuristic to guide itself. In the simple case, it is as fast as Greedy Best-First-Search.
![maze](https://user-images.githubusercontent.com/47361086/126357257-30be57d4-b315-44db-89d4-e474e78cb072.png)

In the standard terminology used when talking about A*, g(n) represents the exact cost of the path from the starting point to any vertex n, and h(n) represents the heuristic estimated cost from vertex n to the goal. In the above diagram, the green oval represents the goal and pink represents vertice of the starting point. A* balances the two as it moves from the starting point to the goal. Each time through the main loop, it examines the vertex n that has the lowest f(n) = g(n) + h(n).

## Installation and Running Procedure
Clone this github repository into the workspace
```
git clone https://github.com/NithaElizabeth/PathPlanning
```
Next install all the necessary libraries .
```
pip install -r requirements.txt
```
After this launch the program
```
python a_star.py
```
## Author
The system was developed by Nitha Elizabeth John. \
Author  : Nitha Elizabeth John \
Contact : nithaelizabethjohn@gmail.com

