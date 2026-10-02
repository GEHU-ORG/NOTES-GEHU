# Week 7: Shortest Path Algorithms

This week's problems focus on different shortest path algorithms and their applications.

## Problem 1: Dijkstra's Algorithm
After end term examination, Akshay wants to party with his friends. All his friends are living as paying guest and it has been decided to first gather at Akshay's house and then move towards party location. The problem is that no one knows the exact address of his house in the city. Akshay as a computer science wizard knows how to apply his theory subjects in his real life and came up with an amazing idea to help his friends. He draws a graph by looking in to location of his house and his friends' location (as a node in the graph) on a map. He wishes to find out shortest distance and path covering that distance from each of his friend's location to his house.

### Input Format:
- Input will be the graph in the form of adjacency matrix or adjacency list
- Source vertex number is also provided as an input

### Output Format:
- Output will contain V lines
- Each line will represent the whole path from destination vertex number to source vertex number along with minimum path weight

## Problem 2: Bellman-Ford Algorithm
Design an algorithm and implement it using a program to solve previous question's problem using Bellman-Ford's shortest path algorithm.

### Input Format:
- Input will be the graph in the form of adjacency matrix or adjacency list
- Source vertex number is also provided as an input

### Output Format:
- Output will contain V lines
- Each line will represent the whole path from destination vertex number to source vertex number along with minimum path weight

## Problem 3: Shortest Path with K Edges
Given a directed graph with two vertices (source and destination), design an algorithm and implement it using a program to find the weight of the shortest path from source to destination with exactly k edges on the path.

### Input Format:
- First input line will obtain number of vertices V present in the graph
- Graph in the form of adjacency matrix or adjacency list is taken as an input in next V lines
- Next input line will obtain source and destination vertex number
- Last input line will obtain value k

### Output Format:
- Output will be the weight of shortest path from source to destination having exactly k edges
- If no path is available then print "no path of length k is available"

## Time Complexities

| Algorithm | Time Complexity | Space Complexity |
|-----------|----------------|------------------|
| Dijkstra's | O((V + E)logV) | O(V) |
| Bellman-Ford | O(VE) | O(V) |
| K-Edges Shortest Path | O(V^k) | O(V) |

Where:
- V = Number of vertices
- E = Number of edges
- k = Number of edges in path 