# Week 4: Advanced Sorting Algorithms

This directory contains implementations of three advanced sorting algorithms and a selection problem:
1. Merge Sort with Comparisons and Inversions
2. Quick Sort with Random Pivot
3. Kth Smallest/Largest Element Finding

## Problem Descriptions

### 1. Merge Sort
Given an unsorted array of integers, sort the array using merge sort and find:
- Number of comparisons
- Number of inversions during sorting
- Time Complexity: O(n log n)
- Space Complexity: O(n)

### 2. Quick Sort
Given an unsorted array of integers, sort the array using quick sort with random pivot selection and find:
- Number of comparisons
- Number of swaps required
- Time Complexity: O(n log n) average, O(n²) worst case
- Space Complexity: O(log n)

### 3. Kth Smallest/Largest Element
Given an unsorted array of integers, find the Kth smallest or largest element in the array.
- Time Complexity: O(n) average, O(n²) worst case
- Space Complexity: O(1)

## Input/Output Format

### 1. Merge Sort
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
Number of inversions
```

### 2. Quick Sort
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

### 3. Kth Smallest/Largest Element
```
Input:
T (number of test cases)
For each test case:
n (size of array)
n space-separated integers
K (position to find)

Output:
For each test case:
Kth smallest/largest element
```

## Sample Input/Output

### 1. Merge Sort
```
Input:
3
8
23 65 21 76 46 89 45 32
10
54 65 34 76 78 97 46 32 51 21
15
63 42 223 645 652 31 324 22 553 12 54 65 86 46 325

Output:
21 23 32 45 46 65 76 89
comparisons = 16
inversions = 12
21 32 34 46 51 54 65 76 78 97
comparisons = 22
inversions = 15
12 22 31 42 46 54 63 65 86 223 324 325 553 645 652
comparisons = 43
inversions = 28
```

### 2. Quick Sort
```
Input:
3
8
23 65 21 76 46 89 45 32
10
54 65 34 76 78 97 46 32 51 21
15
63 42 223 645 652 31 324 22 553 12 54 65 86 46 325

Output:
21 23 32 45 46 65 76 89
comparisons = 14
swaps = 10
21 32 34 46 51 54 65 76 78 97
comparisons = 29
swaps = 21
12 22 31 42 46 54 63 65 86 223 324 325 553 645 652
comparisons = 45
swaps = 39
```

### 3. Kth Smallest/Largest Element
```
Input:
3
10
123 656 54 765 344 514 765 34 765 234
3
15
43 64 13 78 864 346 786 456 21 19 8 434 76 270 601
8

Output:
123
78
```

## How to Compile and Run

```bash
# For Merge Sort
g++ merge_sort.cpp -o merge_sort
./merge_sort

# For Quick Sort
g++ quick_sort.cpp -o quick_sort
./quick_sort

# For Kth Element
g++ kth_element.cpp -o kth_element
./kth_element
``` 