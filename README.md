# NumPy Functions Summary 

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
This functipn returns an array with axes transposed. For a 1-D array, this returns an unchanged view of the original array, as a transposed vector is simply the same vector. 

```python
numpy.transpose(a, axes=None)
#Other Syntax
numpy.T(a, axes=None)
```
### Implementation Example :

```python
# Import required package
import numpy as np
 
a = np.array([[1, 2], [3, 4]])
a
array([[1, 2],
       [3, 4]])
np.transpose(a)
array([[1, 3],
       [2, 4]])
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
stuff stuff

### Dot
the dot product or also known as the scalar product is an algebraic operation that takes two equal-length sequences of numbers and returns a single number using the `np.dot()` function
### Implementation Example :
```python
# Importing numpy module
import numpy as np
 
# Taking two scalar values
a = 5
b = 7
 
# Calculating dot product using dot()
print(np.dot(a, b))
```
### Cross
the dot product or also known as the scalar product is an algebraic operation that takes two equal-length sequences of numbers and returns a single number using the `numpy.cross()` function
### Implementation Example :
```python
# import library
import numpy as np
 
# declare vectors
x = [1, 2]
y = [3, 4]
 
# find cross product of two given vectors
result = np.cross(x, y)
 
# show the result
print(result)
```


# References

> https://www.geeksforgeeks.org/how-to-calculate-the-determinant-of-a-matrix-using-numpy/?ref=header_search
> 
> https://numpy.org/doc/stable/reference/generated/numpy.transpose.html#numpy-transpose
> 
> https://numpy.org/doc/stable/reference/generated/numpy.linalg.inv.html
>
> sum
> 
> https://numpy.org/doc/stable/reference/generated/numpy.dot.html#numpy.dot
>
> https://numpy.org/doc/stable/reference/generated/numpy.cross.html#numpy.cross
