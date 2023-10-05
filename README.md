# problem 1:
**Problem: Maximum Hourglass Sum**

You are given a 2D array representing a 6x6 grid. An hourglass in the grid is defined as a subset of values with indices falling in the following pattern:

```
a b c
  d
e f g
```

Your task is to calculate the maximum hourglass sum in the grid.

Write a Python function called `max_hourglass_sum(grid)` that takes a 6x6 grid (a list of lists) as input and returns the maximum hourglass sum.

Function Signature: `def max_hourglass_sum(grid: List[List[int]]) -> int`

**Input:**

- `grid`: A 6x6 grid of integers where each element is in the range [-9, 9].

**Output:**

- An integer representing the maximum hourglass sum.

**Example:**

```python
grid = [
    [-9, -9, -9, 1, 1, 1],
    [0, -9, 0, 4, 3, 2],
    [-9, -9, -9, 1, 2, 3],
    [0, 0, 8, 6, 6, 0],
    [0, 0, 0, -2, 0, 0],
    [0, 0, 1, 2, 4, 0]
]

max_sum = max_hourglass_sum(grid)
print(max_sum)  # Output should be 28
```

**Constraints:**

- The input grid will always be a valid 6x6 grid with values in the range [-9, 9].
