# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the os and numpy libraries
### Step 2: Define the square matrix A using numpy.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the result

## Program: 
import os 

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy

A=numpy.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,Vectors=numpy.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))

## Output:<img width="1228" height="783" alt="{277A4F9C-051F-4C9D-BC81-0A9AC18E0E33}" src="https://github.com/user-attachments/assets/0685cacf-0cf7-4b5c-84a9-c1c015ad9abc" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
