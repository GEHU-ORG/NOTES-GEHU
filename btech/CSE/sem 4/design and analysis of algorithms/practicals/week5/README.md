# Week 5: Special Problems

This directory contains implementations of three special problems:
1. Maximum Occurring Alphabet
2. Pair Sum Problem
3. Common Elements in Two Sorted Arrays

## Problem Descriptions

### 1. Maximum Occurring Alphabet
Given an unsorted array of alphabets containing duplicate elements, find which alphabet has maximum number of occurrences and print it.
- Time Complexity: O(n)
- Space Complexity: O(1)
- Uses counting sort approach

### 2. Pair Sum Problem
Given an unsorted array of integers, find whether two elements exist such that their sum is equal to the given key element.
- Time Complexity: O(n log n)
- Space Complexity: O(1)
- Uses sorting and two-pointer technique

### 3. Common Elements in Two Sorted Arrays
Given two sorted integer arrays of size m and n, find list of elements which are common to both.
- Time Complexity: O(m + n)
- Space Complexity: O(1)
- Uses two-pointer technique

## Input/Output Format

### 1. Maximum Occurring Alphabet
```
Input:
T (number of test cases)
For each test case:
n (size of array)
n space-separated alphabets

Output:
For each test case:
"alphabet - count" if duplicates exist
"No Duplicates Present" if no duplicates
```

### 2. Pair Sum Problem
```
Input:
T (number of test cases)
For each test case:
n (size of array)
n space-separated integers
key (sum to find)

Output:
For each test case:
"element1 element2" if pair exists
"No Such Elements Exist" if no pair found
```

### 3. Common Elements
```
Input:
m (size of first array)
m space-separated integers (first array)
n (size of second array)
n space-separated integers (second array)

Output:
Space-separated list of common elements
```

## Sample Input/Output

### 1. Maximum Occurring Alphabet
```
Input:
3
10
a e d w a d q a f p
15
r k p g v y u m q a d j c z e
20
g t l l t c w a w g l c w d s a a v c l

Output:
a - 3
No Duplicates Present
l - 4
```

### 2. Pair Sum Problem
```
Input:
2
10
64 28 97 40 12 72 84 24 38 10
50
15
56 10 72 91 29 3 41 45 61 20 11 39 9 12 94
302

Output:
10 40
No Such Elements Exist
```

### 3. Common Elements
```
Input:
7
34 76 10 39 85 10 55
12
30 55 34 72 10 34 10 89 11 30 69 51

Output:
10 10 34 34 55
```

## How to Compile and Run

```bash
# For Maximum Occurring Alphabet
g++ max_occurring_alphabet.cpp -o max_occurring_alphabet
./max_occurring_alphabet

# For Pair Sum Problem
g++ pair_sum.cpp -o pair_sum
./pair_sum

# For Common Elements
g++ common_elements.cpp -o common_elements
./common_elements
``` 