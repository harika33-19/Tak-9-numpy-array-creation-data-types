# NumPy Array Creation and Data Types

**Internship:** Data Science Intern at Veda Technology\
**Progress:** Day 9 of 45

## Objective

Learn the fundamentals of NumPy by creating arrays and exploring their
shape, dimensions, size, data types, and basic numerical operations.

## Tools Used

-   Python
-   NumPy
-   Google Colab / Jupyter Notebook

## Tasks Covered

-   Create one-dimensional (1D) NumPy arrays
-   Create two-dimensional (2D) NumPy arrays
-   Explore array attributes: `shape`, `ndim`, `size`, and `dtype`
-   Perform basic numerical operations on arrays
-   Compare NumPy arrays with Python lists

## Example Code

``` python
import numpy as np

# Create a 1D array
arr1 = np.array([10, 20, 30, 40, 50])
print("1D Array:", arr1)
print("Shape:", arr1.shape)
print("Dimensions:", arr1.ndim)
print("Size:", arr1.size)
print("Data type:", arr1.dtype)

# Create a 2D array
arr2 = np.array([[1, 2, 3], [4, 5, 6]])
print("\n2D Array:\n", arr2)
print("Shape:", arr2.shape)
print("Dimensions:", arr2.ndim)
print("Size:", arr2.size)

# Basic numerical operations
print("Addition:", arr1 + 5)
print("Multiplication:", arr1 * 2)
print("Sum:", np.sum(arr1))
print("Mean:", np.mean(arr1))
```

## Key Learnings

-   `np.array()` creates a NumPy array from a sequence.
-   `shape` gives the array's dimensions along each axis.
-   `ndim` tells how many dimensions the array has.
-   `size` gives the total number of elements.
-   `dtype` shows the type of elements stored in the array.
-   NumPy supports efficient element-wise numerical operations.

## Suggested Dataset

This task can be completed using sample numeric values. The Iris Dataset
or a Student Marks Dataset can also be used for additional practice.

## Repository

Suggested GitHub repository name: `numpy-array-creation-data-types`

Upload your completed notebook (for example, `task9.ipynb`) and this
README file to the repository.

## Internship Hashtags

#Day9Of45 #VedaTechnology #DataScienceIntern #Python #NumPy #GitHub
