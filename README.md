# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
''
#Program to find the rank of a matrix.
#Developed by:Mohan K
#RegisterNumber:212225240087

import numpy as np
A=np.array([[3,2,5],[1,1,2],[3,3,6]])
solution=np.linalg.matrix_rank(A)
print(solution)
''
## Output:
<img width="1312" height="963" alt="Screenshot 2026-02-03 113935" src="https://github.com/user-attachments/assets/f330a614-6b1b-4c9a-a22b-83bb6b69919b" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

