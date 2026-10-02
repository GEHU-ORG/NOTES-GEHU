# Week 11: Dynamic Programming Problems

This week's problems focus on various dynamic programming applications.

## Problem 1: Matrix Chain Multiplication
Given a sequence of matrices, write an algorithm to find most efficient way to multiply these matrices together. To find the optimal solution, you need to find the order in which these matrices should be multiplied.

### Input Format:
- First line of input will take number of matrices n that you need to multiply
- For each line i in n, take two inputs which will represent dimensions aXb of matrix i

### Output Format:
- Output will be the minimum number of operations that are required to multiply the list of matrices

## Problem 2: Coin Change
Given a set of available types of coins. Let suppose you have infinite supply of each type of coin. For a given value N, you have to design an algorithm and implement it using a program to find number of ways in which these coins can be added to make sum value equals to N.

### Input Format:
- First line of input will take number of coins that are available
- Second line of input will take the value of each coin
- Third line of input will take the value N for which you need to find sum

### Output Format:
- Output will be the number of ways

## Problem 3: Equal Sum Partition
Given a set of elements, you have to partition the set into two subsets such that the sum of elements in both subsets is same. Design an algorithm and implement it using a program to solve this problem.

### Input Format:
- First line of input will take number of elements n present in the set
- Second line of input will take n space-separated elements of the set

### Output Format:
- Output will be 'yes' if two such subsets found otherwise print 'no'

## Time Complexities

| Algorithm | Time Complexity | Space Complexity |
|-----------|----------------|------------------|
| Matrix Chain Multiplication | O(n^3) | O(n^2) |
| Coin Change | O(n*sum) | O(sum) |
| Equal Sum Partition | O(n*sum) | O(sum) |

Where:
- n = Number of matrices/coins/elements
- sum = Target sum value 