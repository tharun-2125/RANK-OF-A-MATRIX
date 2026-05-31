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
#Program to find the rank of a matrix.
~~~
#Developed by: THARUN N
#RegisterNumber:212225240173
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[1,2,3],[3,6,9]])
solution=np.linalg.matrix_rank(a)
print(solution)
~~~
## Output:
<img width="832" height="807" alt="image" src="https://github.com/user-attachments/assets/d7f80225-5f5c-4f2e-84fa-cf7785b19cd8" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

