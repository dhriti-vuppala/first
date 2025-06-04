# NumPy Array Demonstration

This code demonstrates the creation and inspection of various NumPy arrays, showcasing their structure, dimensionality, and default value initialization.

## 📁 Description

The script includes:
- A **4D NumPy array** using `np.array`
- Use of `np.zeros` to create a matrix of zeros
- Use of `np.ones` to create a matrix of ones

## 🧠 Code Explanation

```python
import numpy as np

# Create a 4D NumPy array
a = np.array([[[[1,2,3],[4,5,6],[7,8,9],[10,11,12]]]])
print(a)             # Print the array
print(type(a))       # Check the type
print(a.ndim)        # Check the number of dimensions (should be 4)

# Create a 3x3 array of zeros
c = np.zeros((3,3))
print(c)

# Create a 2x4 array of ones
d = np.ones((2,4))
print(d)
