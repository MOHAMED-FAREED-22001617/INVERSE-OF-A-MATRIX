# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Imort numpy as np
### Step 2: 
Assign in np.array() in inverse of matrix
### Step 3: 
Using the np.linalg.matrix_rank(),we can find the inverse of given matrix.
### Step 4: 
Print the value and end the program.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: MOHAMED FAREED F
#RegisterNumber: 22001617
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
result=np.linalg.inv(A)
print(result)
```
## Output:
!['output'](/Screenshot%20from%202022-12-31%2018-31-23.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program