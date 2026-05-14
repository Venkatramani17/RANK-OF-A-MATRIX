# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: R.Venkatramani
#RegisterNumber: 212225240182
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array([[5, -3, -10],
              [2,  2,  -3],
              [-3, -1,  5]])
rank = np.linalg.matrix_rank(A)

print(rank)
```
## Output:
<img width="1209" height="788" alt="image" src="https://github.com/user-attachments/assets/2ce7aba8-9a70-4e92-88de-d9df9e7dd393" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

