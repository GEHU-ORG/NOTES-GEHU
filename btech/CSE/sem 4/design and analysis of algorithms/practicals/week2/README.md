# Week 2: Advanced Searching Algorithms

This directory contains implementations of three advanced searching algorithms:
1. Binary Search with Duplicate Elements
2. Finding Three Indices (i,j,k) such that arr[i] + arr[j] = arr[k]
3. Counting Pairs with Given Difference

## Problem Descriptions

### 1. Binary Search with Duplicate Elements
Given a sorted array of positive integers containing few duplicate elements, find whether the given key element is present in the array or not. If present, also find the number of copies of the given key.
- Time Complexity: O(log n)
- Space Complexity: O(1)

### 2. Finding Three Indices
Given a sorted array of positive integers, find three indices i, j, k such that arr[i] + arr[j] = arr[k].
- Time Complexity: O(n²)
- Space Complexity: O(1)

### 3. Counting Pairs with Given Difference
Given an array of nonnegative integers, count the number of pairs of integers such that their difference is equal to a given key, K.
- Time Complexity: O(n log n)
- Space Complexity: O(1)

## Input/Output Format

### 1. Binary Search with Duplicates
```
Input:
T (number of test cases)
For each test case:
n (size of array)
n space-separated integers
key (element to search)

Output:
For each test case:
"key - count" if key is present
"Key not present" if key is not found
```

### 2. Finding Three Indices
```
Input:
T (number of test cases)
For each test case:
n (size of array)
n space-separated integers

Output:
For each test case:
"i, j, k" if found
"No sequence found" if not found
```

### 3. Counting Pairs with Difference
```
Input:
T (number of test cases)
For each test case:
n (size of array)
n space-separated integers
K (difference to find)

Output:
For each test case:
Total count of pairs with difference K
```

## Sample Input/Output

### 1. Binary Search with Duplicates
```
Input:
2
10
235 235 278 278 763 764 790 853 981 981
981
15
1 2 2 3 3 5 5 5 25 75 75 75 97 97 97
75

Output:
981 - 2
75 - 3
```

### 2. Finding Three Indices
```
Input:
3
5
1 5 84 209 341
10
24 28 48 71 86 89 92 120 194 201
15
64 69 82 95 99 107 113 141 171 350 369 400 511 590 666

Output:
No sequence found
2, 7, 8
1, 6, 9
```

### 3. Counting Pairs with Difference
```
Input:
2
5
1 51 84 21 31
20
10
24 71 16 92 12 28 48 14 20 22
4

Output:
2
4
```

## How to Compile and Run

```bash
# For Binary Search with Duplicates
g++ binary_search_duplicates.cpp -o binary_search_duplicates
./binary_search_duplicates

# For Finding Three Indices
g++ find_three_indices.cpp -o find_three_indices
./find_three_indices

# For Counting Pairs with Difference
g++ count_pairs_diff.cpp -o count_pairs_diff
./count_pairs_diff
``` 