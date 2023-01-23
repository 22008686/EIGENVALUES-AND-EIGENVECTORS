# EIGENVALUES-AND-EIGENVECTORS
## Aim:

To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm: 

step 1:Import numpy package
step 2:Get the eigen values
step 3:Using the np.linalg.eig(),we get two results (first is eigen value and second is eigen vector) of the given matrix
step 4:Print the result

## Program:

```python
Program to find the eigen values and eigen vectors.
#Developed by: Pavithra.M
#RegisterNumber: 22008686
import numpy as np
A= np.array([[2,2],[1,3]])
values, vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![output](eigen.png)

## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program
