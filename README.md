# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from the matrix and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program.
## Program:
#Program to find the rank of a matrix.
#Developed by: SIDDHARTH N N 
#RegisterNumber: 212225240148
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
matrix_A = np.array([[1,2,3], [3,6,9]])
rank = np.linalg.matrix_rank(matrix_A)
print(rank)
## Output:
<img width="946" height="467" alt="Screenshot 2026-05-05 131537" src="https://github.com/user-attachments/assets/1ff6b9f3-0cef-473f-bb26-9e4580b535b0" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

