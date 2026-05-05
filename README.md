# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Input the matrix
### Step 2: Form characteristic equation
### Step 3: Find eigenvalues
### Step 4: Find eigenvectors

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: SHREYAS M
#RegisterNumber: 212225230264

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eig_values,eig_vector=np.linalg.eig(matrix)
print(f"Eigen values are {eig_values} and Eigen Vectors are {eig_vector}")
~~~
## Output:
<img width="1919" height="973" alt="image" src="https://github.com/user-attachments/assets/51f4d60d-a84d-4cc5-aaa0-725c332af1be" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
