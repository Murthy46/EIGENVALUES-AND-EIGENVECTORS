# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation
### Step 2:
Get the input matrix from the user
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:Sundaramurthy M 
#RegisterNumber:212222233006

import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
<img width="1440" alt="Screenshot 2023-11-15 at 9 48 33 PM" src="https://github.com/Murthy46/EIGENVALUES-AND-EIGENVECTORS/assets/145112768/2df95265-1b31-478e-a382-d65040caf9ec">

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
