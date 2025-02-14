# W9D1 **ChatGPT helped with this
# Algorithm Analysis and Optimization

## Overview
This project contains the implementation and analysis of two algorithms: Linear Search and Bubble Sort. We analyze their time complexities, identify inefficiencies, and propose optimizations where applicable.

## Algorithms

### Linear Search

#### Description
Given an unsorted array of integers and a target value, the Linear Search algorithm finds the index of the first occurrence of the target value in the array. If the target value is not found, it returns -1.

#### Time Complexity
The time complexity of Linear Search is **O(n)**, where *n* is the number of elements in the array. This is because in the worst case, the algorithm has to check each element once.

#### Implementation
```python
def linear_search(arr, target):
    for index, value in enumerate(arr):
        if value == target:
            return index
    return -1

# Sample Test Cases
array = [10, 23, 45, 70, 11, 15]
target = 70
print(f"Index of {target}: {linear_search(array, target)}")  # Output: 3

target = 11
print(f"Index of {target}: {linear_search(array, target)}")  # Output: 4

target = 99
print(f"Index of {target}: {linear_search(array, target)}")  # Output: -1

Documentation and Analysis
Time Complexity Analysis
Linear Search: O(n)
Bubble Sort: O(n^2)
Optimized Bubble Sort: O(n^2) worst case, O(n) best case

Running the Code
Ensure you have Python installed on your system.
Save the provided code in a .py file.
Run the file using the command python <filename>.py in your terminal.
Observe the output for the provided test cases.