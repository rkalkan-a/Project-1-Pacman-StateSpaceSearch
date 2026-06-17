# Project-1-Pacman-StateSpaceSearch
Team R.M.R. Project 1

CPSC 481 – Artificial Intelligence

A Pacman agent that finds paths through a maze using general-purpose search algorithms. Built on the UC Berkeley CS188 Pacman framework.

Team R.E.M: Ronan Kalkan, Manuel Camorlinga, Ryan Maffey

## What's Implemented

All work is in search.py:

- Q1 — Depth-First Search (depthFirstSearch), uses a Stack
- Q2 — Breadth-First Search (breadthFirstSearch), uses a Queue

Both are graph searches that track visited states so the same state is never expanded twice. Each entry stores the state plus the actions taken to reach it, so the full path can be returned once the goal is found.

## How to Run

Run these from inside the project folder.

Depth-First Search (Q1):

    python3 pacman.py -l tinyMaze -p SearchAgent
    python3 pacman.py -l mediumMaze -p SearchAgent
    python3 pacman.py -l bigMaze -p SearchAgent -z .5

Breadth-First Search (Q2):

    python3 pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
    python3 pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5

Add -q to any command for quiet text output with no graphics window.

