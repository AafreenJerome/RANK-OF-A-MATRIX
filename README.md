# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy module using import numpy as np.
### Step 2: Create a NumPy array containing the elements of the given matrix.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Print the rank of the matrix and end the program.
## Program:
Program to find the rank of a matrix.

Developed by: AAFREEN JEROME

RegisterNumber:26007104

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A=np.array([[1,2,3],[3,6,9]])

s=np.linalg.matrix_rank(A)

print(s)

## Output:

<img width="937" height="731" alt="image" src="https://github.com/user-attachments/assets/1eae0df9-8b42-4eca-b0d9-0514cf82d1de" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

