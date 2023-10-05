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


------------------------------------------

# Problem 2
Certainly! Here's a blueprint for a question where the coder is asked to create classes based on the given specifications:

**Problem: Student Grade Calculation**

You are tasked with designing two classes, `Person` and `Student`, to manage student information and calculate grades based on test scores. Below are the requirements for each class:

**Class: Person**

- Attributes:
  - `firstName` (str): The first name of the person.
  - `lastName` (str): The last name of the person.
  - `id` (int): The person's ID number.
  
- Methods:
  - `__init__(self, firstName, lastName, idNumber)`: Constructor that initializes the attributes.
  - `display_info(self)`: Method that displays information about the person.

**Class: Student (Inherits from Person)**

- Additional Attributes:
  - `scores` (list of int): An array of test scores for the student.
  
- Additional Methods:
  - `__init__(self, firstName, lastName, idNumber, scores)`: Constructor that initializes attributes of both `Person` and `Student`.
  - `calculate(self)`: Method that calculates the grade based on the average score and returns a character representing the grade.
  
Grades are calculated as follows:
- If the average score is >= 90, return "O" (Outstanding).
- If the average score is >= 80, return "E" (Excellent).
- If the average score is >= 70, return "A" (Average).
- If the average score is >= 55, return "P" (Pass).
- If the average score is >= 40, return "D" (Deficient).
- Otherwise, return "T" (Terrible).

Your task is to implement the `Person` and `Student` classes according to the given specifications.

**Class Signature for Person:** `class Person:`

**Class Signature for Student (Inherits from Person):** `class Student(Person):`

Please complete the classes and methods as described above. You can use this blueprint to implement the classes and solve the problem.

# Problem 3 ( coming Soon )

