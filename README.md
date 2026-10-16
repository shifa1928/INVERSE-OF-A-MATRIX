# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program
#Program to find the inverse of a matrix.
#Developed by: M SHIFA
#RegisterNumber:26003336
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
r=np.linalg.inv(A)
print(r)
## Output:
<img width="965" height="539" alt="{5CAAC8E2-69B9-436D-9D97-BA2E775F5B80}" src="https://github.com/user-attachments/assets/12f2e1f8-d0a3-4be5-bb5f-2181e1ed4315" />
<img width="593" height="228" alt="{52EE384F-1A8E-43CC-9C0C-880DF3C740DF}" src="https://github.com/user-attachments/assets/1ef57e11-282d-49c9-bd50-d26842e1eb03" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

