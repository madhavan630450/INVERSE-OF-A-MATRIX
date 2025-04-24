# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Check if the matrix is square and calculate the determinant.
### Step 2: If the determinant is non-zero, calculate the adjugate matrix by finding the cofactors and transposing.
### Step 3: Divide each element of the adjugate matrix by the determinant.
### Step 4:Return the resulting matrix as the inverse. 

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: MARIMUTHU MATHAVAN
#RegisterNumber:212224230153
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
result=np.linalg.inv(A)
print(result)
```
## Output:
![image](https://github.com/user-attachments/assets/4e29a3ba-e06f-42f2-b310-644b600d6ae4)

## Result:
Thus the inverse of given matrix is successfully solved using python program

