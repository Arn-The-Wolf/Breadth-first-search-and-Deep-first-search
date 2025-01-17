# Search Algorithms: Depth-First Search (DFS) and Breadth-First Search (BFS)

This repository demonstrates and explains the two popular graph traversal algorithms: **Depth-First Search (DFS)** and **Breadth-First Search (BFS)**.

## Table of Contents
1. [Overview](#overview)
2. [Depth-First Search (DFS)](#depth-first-search-dfs)
3. [Breadth-First Search (BFS)](#breadth-first-search-bfs)
4. [Comparison](#comparison)
5. [Usage](#usage)
6. [License](#license)

---

## Overview

Depth-First Search (DFS) and Breadth-First Search (BFS) are algorithms for traversing or searching tree or graph data structures. Both algorithms start at a specific node and explore the graph, but they differ in the order of node exploration:

- **DFS** explores as far as possible down one branch before backtracking.
- **BFS** explores all nodes at the present depth level before moving on to nodes at the next depth level.

Both algorithms can be used to solve various problems such as pathfinding, cycle detection, and finding connected components in graphs.

---

## Depth-First Search (DFS)

### Explanation
DFS is a traversal algorithm that starts at the root (or an arbitrary node in the case of a graph) and explores as far as possible along each branch before backtracking.

DFS can be implemented using a stack (either explicitly or through recursion). It is commonly used for problems like:
- Pathfinding
- Topological Sorting
- Cycle Detection

### Pseudocode
