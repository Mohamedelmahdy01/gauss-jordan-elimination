# Gauss-Jordan Elimination

This Python script implements the Gauss-Jordan elimination method for solving systems of linear equations. It takes coefficient matrices `a` and constant vectors `b` as input and returns the solution(s) or indicates if the system has no solution or infinite solutions.

## Usage

To use this script, follow these steps:

1. Make sure you have Python installed on your system.
2. Install the required dependencies (`numpy`).
    ```bash
    pip install numpy
    ```
3. Copy the `gaussjordan` function into your project or import it directly.
4. Create coefficient matrix `a` and constant vector `b` for your system of linear equations.
5. Call the `gaussjordan` function with `a` and `b` as arguments.

Example:
```python
import numpy as np

def gaussjordan(a, b):
    # Implementation here...

a = [[0, 2, 9, 5],
     [4, 6, 2, 5],
     [1, 5, 4, 8],
     [3, 4, 7, 5]]
b = [2, 6, 9, 3]

print(gaussjordan(a, b)) 
```


