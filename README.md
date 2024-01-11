# NumPy 

## Determinant


A special number that can be calculated from a square matrix is known as the Determinant of a square matrix. The Numpy provides us the feature to calculate the determinant of a square matrix using this function.
```python
numpy.linalg.det()
```

### Implementation Example :
We will be calculating Determinant of a 2X2 Numpy matrix using `numpy.linalg.det()` function
```python
# importing Numpy package 
import numpy as np 
  
# creating a 2X2 Numpy matrix 
n_array = np.array([[50, 29], [30, 44]]) 
  
# Displaying the Matrix 
print("Numpy Matrix is:") 
print(n_array) 
  
# calculating the determinant of matrix 
det = np.linalg.det(n_array) 
  
print("\nDeterminant of given 2X2 matrix:") 
print(int(det)) 
```
## Transpose
transpose is a function in the NumPy library that computes the transpose of a matrix. It swaps the rows and columns of the matrix, effectively reflecting it along its main diagonal. 

The function is called on a NumPy matrix object, and it does not take any parameters. The result is a new matrix representing the transposed version of the original matrix.
```python
numpy.matrix.transpose()
```
### Implementation Example :
the code uses the NumPy library to create a 2×3 matrix. It then calculates the transpose of the original matrix using the `transpose()` function. Finally, it prints both the original and transposed matrices to the console.
import numpy as np
```python 
# Original matrix
original_matrix = np.matrix([[1, 2, 3], [4, 5, 6]])
 
# Transposed matrix
transposed_matrix = original_matrix.transpose()
 
print("Original Matrix:")
print(original_matrix)
print("\nTransposed Matrix:")
print(transposed_matrix)
```
## Inverse
The inverse of a matrix is that matrix which when multiplied with the original matrix will give an identity matrix

Python provides a very easy method to calculate the inverse of a matrix. The function is available in the NumPy module and is used to compute the inverse matrix in Python.
   
```python
numpy.linalg.inv()
```
### Implementation Example :
we will create multiple NumPy array matrices and then convert them into their inverse matrices using `np.linalg.inv()` function.
```python
# Import required package
import numpy as np
 
# Inverses of several matrices can
# be computed at once
A = np.array([[[1., 2.], [3., 4.]],
              [[1, 3], [3, 5]]])
 
# Calculating the inverse of the matrix
print(np.linalg.inv(A))
```

## Operations with vectors 
### Sum
### Dot
### Cross



# References

> https://www.geeksforgeeks.org/how-to-calculate-the-determinant-of-a-matrix-using-numpy/?ref=header_search
> 
> https://www.geeksforgeeks.org/python-numpy-matrix-transpose/?ref=header_search
> 
> https://www.geeksforgeeks.org/how-to-inverse-a-matrix-using-numpy/
