# Implementing BFS and A* algorithms on Pac-man maze
I wrote this project for "Artificial Intelligence" course that I took in my university. In this project, BFS and A* algorithm are implemented in order to get Pac-man to the goal. Pac-man can move in four directions which are 'North', 'South', 'East', and 'West' ('Stop' is not considered). Legal actions that Pac-man can take depends on Pac-man's situation. For example, If East and South side of Pac-man is blocked by wall, legal-actions are 'North' and 'west'. So, considering legal-action as a node, Pac-man visits unexplored area in BFS order and reach to the goal. In case of A*, I implemented A* algorithm only.

You can run the code with the following commands:
- `python3 pacman.py -p BFSAgent`
- `python3 pacman.py -p AstarAgent`
