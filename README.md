# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy 
### Step 2: 
assign values
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the output
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:N.bharath 
#RegisterNumber:23003413
import numpy as np
A=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors) 
```
## Output:
![output](https://github.com/BHARATHNATRAJAN/EIGENVALUES-AND-EIGENVECTORS/assets/147473529/1bbd29d0-3350-4290-864f-e2dbe9353e23)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
