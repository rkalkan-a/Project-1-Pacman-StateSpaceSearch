CPSC 481 - Artificial Intelligence
Project 1 - State Space Search for Pacman

Team Name: R.E.M

Team Members:
- Ronan Kalkan
- Manuel Camorlinga
- Ryan Maffey

Completed work:
- Question 1: Depth-First Search (depthFirstSearch in search.py)
- Question 2: Breadth-First Search (breadthFirstSearch in search.py)
  (Questions 3-8 were not required for this project.)

Notes:
- DFS uses a util.Stack (LIFO) fringe; BFS uses a util.Queue (FIFO) fringe.
- Both are graph searches that track visited states to avoid re-expansion.
- Verified results:
    DFS mediumMaze path cost = 130
    BFS mediumMaze path cost = 68 (least-cost)
    Official test_cases q1: 3/3, q2: 3/3
