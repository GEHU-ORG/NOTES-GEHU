# Week 6: Graph Algorithms

This week's problems focus on fundamental graph algorithms and their applications.

## Problem 1: Path Existence Check
Given a (directed/undirected) graph, design an algorithm and implement it using a program to find if a path exists between two given vertices or not using DFS.

### Input Format:
- Input will be the graph in the form of adjacency matrix or adjacency list
- Source vertex number and destination vertex number is also provided as an input

### Output Format:
- Output will be 'Yes Path Exists' if path exists, otherwise print 'No Such Path Exists'

## Problem 2: Bipartite Graph Check
Given a graph, design an algorithm and implement it using a program to find if a graph is bipartite or not using BFS.

### Input Format:
- Input will be the graph in the form of adjacency matrix or adjacency list

### Output Format:
- Output will be 'Yes Bipartite' if graph is bipartite, otherwise print 'Not Bipartite'

## Problem 3: Cycle Detection
Given a directed graph, design an algorithm and implement it using a program to find whether cycle exists in the graph or not.

### Input Format:
- Input will be the graph in the form of adjacency matrix or adjacency list

### Output Format:
- Output will be 'Yes Cycle Exists' if cycle exists otherwise print 'No Cycle Exists'

## Time Complexities

| Algorithm | Time Complexity | Space Complexity |
|-----------|----------------|------------------|
| DFS Path Check | O(V + E) | O(V) |
| BFS Bipartite Check | O(V + E) | O(V) |
| Cycle Detection | O(V + E) | O(V) |

Where:
- V = Number of vertices
- E = Number of edges 