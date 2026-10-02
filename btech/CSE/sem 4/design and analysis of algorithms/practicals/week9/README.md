# Week 9: Advanced Graph Algorithms and Greedy Problems

This week's problems focus on Floyd-Warshall algorithm and greedy approaches to solve optimization problems.

## Problem 1: Floyd-Warshall Algorithm
Given a graph, design an algorithm and implement it using a program to implement Floyd-Warshall all pair shortest path algorithm.

### Input Format:
- The first line of input takes number of vertices in the graph
- Input will be the graph in the form of adjacency matrix or adjacency list
- If a direct edge is not present between any pair of vertex (u,v), then this entry is shown as AdjM[u,v] = INF

### Output Format:
- Output will be shortest distance matrix in the form of V X V matrix, where each entry (u,v) represents shortest distance between vertex u and vertex v

## Problem 2: Fractional Knapsack
Given a knapsack of maximum capacity w. N items are provided, each having its own value and weight. You have to design an algorithm and implement it using a program to find the list of the selected items such that the final selected content has weight w and has maximum value. You can take fractions of items, i.e. the items can be broken into smaller pieces.

### Input Format:
- First input line will take number of items N which are provided
- Second input line will contain N space-separated array containing weights of all N items
- Third input line will contain N space-separated array containing values of all N items
- Last line of the input will take the maximum capacity w of knapsack

### Output Format:
- First output line will give maximum value that can be achieved
- Next Line of output will give list of items selected along with their fraction of amount which has been taken

## Problem 3: File Merging
Given an array of elements. Assume arr[i] represents the size of file i. Write an algorithm and a program to merge all these files into single file with minimum computation. For given two files A and B with sizes m and n, computation cost of merging them is O(m+n).

### Input Format:
- First line will take the size n of the array
- Second line will take array as input

### Output Format:
- Output will be the minimum computation cost required to merge all the elements of the array

## Time Complexities

| Algorithm | Time Complexity | Space Complexity |
|-----------|----------------|------------------|
| Floyd-Warshall | O(V^3) | O(V^2) |
| Fractional Knapsack | O(n log n) | O(n) |
| File Merging | O(n log n) | O(n) |

Where:
- V = Number of vertices
- n = Number of items/files 