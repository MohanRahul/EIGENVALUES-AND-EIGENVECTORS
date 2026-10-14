# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : imort the os and numpy libraries
### Step 2:  Define the square matrix A using numpy.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the result

## Program:
import os  

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy

A=numpy.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,Vectors=numpy.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))
## Output:<img width="1222" height="739" alt="{A5CEC67C-8165-4FC0-8E21-BAA80B49D008}" src="https://github.com/user-attachments/assets/477a545b-b930-4921-b043-17657fa89cbc" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
