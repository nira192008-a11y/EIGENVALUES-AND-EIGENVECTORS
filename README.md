# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : Start the program.

### Step 2: Import the NumPy library and define the matrix \(A\).

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: Import the NumPy library and define the matrix \(A\).

## Program:

Program to find the eigen values and eigen vectors.

Developed by: Niranjan.p

RegisterNumber:26006895

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a=np.array([[2,2],[1,3]])

values,vectors=np.linalg.eig(a)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:
<img width="1222" height="693" alt="image" src="https://github.com/user-attachments/assets/4bd8751b-3f20-4151-b606-a60026e737ef" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
