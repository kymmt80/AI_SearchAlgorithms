# Search Algorithms

In this project, the aim is to solve a problem using various search algorithms and compare their qualities. BFS, IDS and A* are the algorithms used for this problem.

## Problem Description

A player starts at location (0,0) of a $n\times m$ map. some cells are blocked by obstacles. at each steps, the player can choose to move up, down, left or right if the path is not blocked by walls or obstacles. each cell may contain one of the following elements:

  - <b>Potion:</b> When a player enters a cell with potion, he collects the potion.
    
    
  - <b>Pill:</b> When a player enters a cell with pill, he consumes the pill and a new player appears at location (n-1,0). afterward, only one of the players may move at each step 
    
The goal is to gather all players at location (n-1,m-1) and collect all of the potions in the map.

## Table of Contents

- Problem Description
- Modeling
    - Model Implementation
- Breadth-First Search (BFS)
    - Algorithm
    - Pros and Cons
    - Implementation
    - Tests
    - Overall Results
- Iterative Deepening Search (IDS)
    - Algorithm
    - Pros and Cons
    - Implementation
    - Tests
    - Overall Results
- A*
    - Algorithm
        - heuristic function
    - Pros and Cons
    - Implementation
    - Tests
    - Overall Results
- Weighted A*
- Conclusion