# Week 10: Activity Selection and Task Scheduling

This week's problems focus on activity selection and task scheduling problems using greedy approaches.

## Problem 1: Activity Selection
Given a list of activities with their starting time and finishing time. Your goal is to select maximum number of activities that can be performed by a single person such that selected activities must be non-conflicting. Any activity is said to be non-conflicting if starting time of an activity is greater than or equal to the finishing time of the other activity. Assume that a person can only work on a single activity at a time.

### Input Format:
- First line of input will take number of activities N
- Second line will take N space-separated values defining starting time for all the N activities
- Third line of input will take N space-separated values defining finishing time for all the N activities

### Output Format:
- Output will be the number of non-conflicting activities and the list of selected activities

## Problem 2: Task Scheduling with Deadlines
Given a long list of tasks. Each task takes specific time to accomplish it and each task has a deadline associated with it. You have to design an algorithm and implement it using a program to find maximum number of tasks that can be completed without crossing their deadlines and also find list of selected tasks.

### Input Format:
- First line will give total number of tasks n
- Second line of input will give n space-separated elements of array representing time taken by each task
- Third line of input will give n space-separated elements of array representing deadline associated with each task

### Output Format:
- Output will be the total number of maximum tasks that can be completed

## Problem 3: Majority Element and Median
Given an unsorted array of elements, design an algorithm and implement it using a program to find whether majority element exists or not. Also find median of the array. A majority element is an element that appears more than n/2 times, where n is the size of array.

### Input Format:
- First line of input will give size n of array
- Second line of input will take n space-separated elements of array

### Output Format:
- First line of output will be 'yes' if majority element exists, otherwise print 'no'
- Second line of output will print median of the array

## Time Complexities

| Algorithm | Time Complexity | Space Complexity |
|-----------|----------------|------------------|
| Activity Selection | O(n log n) | O(n) |
| Task Scheduling | O(n log n) | O(n) |
| Majority Element & Median | O(n) | O(1) |

Where:
- n = Number of activities/tasks/elements 