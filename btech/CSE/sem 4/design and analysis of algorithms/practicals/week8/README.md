# Week 8: Minimum Spanning Tree Algorithms

This week's problems focus on different minimum spanning tree algorithms and their applications.

## Problem 1: Prim's Algorithm
Assume that a project of road construction to connect some cities is given to your friend. Map of these cities and roads which will connect them (after construction) is provided to him in the form of a graph. Certain amount of rupees is associated with construction of each road. Your friend has to calculate the minimum budget required for this project. The budget should be designed in such a way that the cost of connecting the cities should be minimum and number of roads required to connect all the cities should be minimum (if there are N cities then only N-1 roads need to be constructed).

### Input Format:
- The first line of input takes number of vertices in the graph
- Input will be the graph in the form of adjacency matrix or adjacency list

### Output Format:
- Output will be minimum spanning weight

## Problem 2: Kruskal's Algorithm
Implement the previous problem using Kruskal's algorithm.

### Input Format:
- The first line of input takes number of vertices in the graph
- Input will be the graph in the form of adjacency matrix or adjacency list

### Output Format:
- Output will be minimum spanning weight

## Problem 3: Maximum Spanning Tree
Assume that same road construction project is given to another person. The amount he will earn from this project is directly proportional to the budget of the project. This person is greedy, so he decided to maximize the budget by constructing those roads who have highest construction cost. Design an algorithm and implement it using a program to find the maximum budget required for the project.

### Input Format:
- The first line of input takes number of vertices in the graph
- Input will be the graph in the form of adjacency matrix or adjacency list

### Output Format:
- Output will be maximum spanning weight

## Time Complexities

| Algorithm | Time Complexity | Space Complexity |
|-----------|----------------|------------------|
| Prim's | O((V + E)logV) | O(V) |
| Kruskal's | O(ElogE) | O(V) |
| Maximum Spanning Tree | O((V + E)logV) | O(V) |

Where:
- V = Number of vertices
- E = Number of edges 