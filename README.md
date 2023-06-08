# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 : Import the numpy module to use the built-in functions for calculation
## Step 2: Get the input matrix from the user
## step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4: End the program

## Program:
```py
# Program to find the eigen values and eigen vectors.
# Developed by: Karthikeyan R
# RegisterNumber:212222240045
import  numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![mathsex4](https://github.com/karthikeyan-R16/EIGENVALUES-AND-EIGENVECTORS/assets/119421232/a0620a6d-4e01-4281-93e6-9b7d3383b254)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
