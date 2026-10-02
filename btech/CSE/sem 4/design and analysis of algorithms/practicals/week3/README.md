# Week 3: Basic Sorting Algorithms

This directory contains implementations of three basic sorting algorithms and a duplicate detection problem:
1. Insertion Sort with Comparisons and Shifts
2. Selection Sort with Comparisons and Swaps
3. Duplicate Element Detection using Sorting

## Problem Descriptions

### 1. Insertion Sort
Given an unsorted array of integers, sort the array using insertion sort and find:
- Number of comparisons
- Number of shifts (total number of times array elements are shifted)
- Time Complexity: O(n²)
- Space Complexity: O(1)

### 2. Selection Sort
Given an unsorted array of integers, sort the array using selection sort and find:
- Number of comparisons
- Number of swaps required
- Time Complexity: O(n²)
- Space Complexity: O(1)

### 3. Duplicate Detection
Given an unsorted array of positive integers, find whether there are any duplicate elements in the array using sorting.
- Time Complexity: O(n log n)
- Space Complexity: O(1)

## Input/Output Format

### 1. Insertion Sort
```
Input:
T (number of test cases)
For each test case:
n (size of array)
n space-separated integers

Output:
For each test case:
Sorted array
Number of comparisons
Number of shifts
```

### 2. Selection Sort
```
Input:
T (number of test cases)
For each test case:
n (size of array)
n space-separated integers

Output:
For each test case:
Sorted array
Number of comparisons
Number of swaps
```

### 3. Duplicate Detection
```
Input:
T (number of test cases)
For each test case:
n (size of array)
n space-separated integers

Output:
For each test case:
'YES' if duplicates are present
'NO' if no duplicates
```

## Sample Input/Output

### 1. Insertion Sort
```
Input:
3
8
-23 65 -31 76 46 89 45 32
10
54 65 34 76 78 97 46 32 51 21
15
63 42 223 645 652 31 324 22 553 -12 54 65 86 46 325

Output:
-31 -23 32 45 46 65 76 89
comparisons = 13
shifts = 20
21 32 34 46 51 54 65 76 78 97
comparisons = 28
shifts = 37
-12 22 31 42 46 54 63 65 86 223 324 325 553 645 652
comparisons = 54
shifts = 68
```

### 2. Selection Sort
```
Input:
3
8
-13 65 -21 76 46 89 45 12
10
54 65 34 76 78 97 46 32 51 21
15
63 42 223 645 652 31 324 22 553 12 54 65 86 46 325

Output:
-21 -13 12 45 46 65 76 89
comparisons = 28
swaps = 7
21 32 34 46 51 54 65 76 78 97
comparisons = 45
swaps = 9
12 22 31 42 46 54 63 65 86 223 324 325 553 645 652
comparisons = 105
swaps = 14
```

### 3. Duplicate Detection
```
Input:
3
5
28 52 83 14 75
10
75 65 1 65 2 6 86 2 75 8
15
75 35 86 57 98 23 73 1 64 8 11 90 61 19 20

Output:
NO
YES
NO
```

## How to Compile and Run

```bash
# For Insertion Sort
g++ insertion_sort.cpp -o insertion_sort
./insertion_sort

# For Selection Sort
g++ selection_sort.cpp -o selection_sort
./selection_sort

# For Duplicate Detection
g++ duplicate_detection.cpp -o duplicate_detection
./duplicate_detection
``` 