# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions
### Step 2: Prepare the Lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program:
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
<img width="1140" height="651" alt="{D2F95EFB-D2DF-40F4-B8AF-84D3047558DC}" src="https://github.com/user-attachments/assets/cf4bac23-219b-4a64-b60f-2cc8e18afb3c" />
<img width="780" height="215" alt="{8D7CE454-A444-4D30-B151-9C9EDA951E2D}" src="https://github.com/user-attachments/assets/144672b3-5560-4f1f-aba0-bb4040ae262b" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

