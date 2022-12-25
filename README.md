# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: sivaram R
#RegisterNumber:22008680
import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
res=np.linalg.inv(A)
print(res)
```
## Output:
![inverse](https://user-images.githubusercontent.com/121165794/209474292-8a249b3d-b4c0-4064-9237-9067b804954c.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program

