# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Define the matrix
### Step 2: 
Apply Gaussian elimination to obtain the row-echelon form
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
Count the non-zero singular values to determine the rank
### Step 4: 
Print the rank of the matrix
## Program:
``````
import numpy as np
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
B=np.linalg.matrix_rank(A)
print(B)
``````
## Output:
![Screenshot 2023-12-14 103708](https://github.com/vinodhini-17/RANK-OF-A-MATRIX/assets/145742741/34fac387-1d57-4b73-b50f-6832693b4712)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

