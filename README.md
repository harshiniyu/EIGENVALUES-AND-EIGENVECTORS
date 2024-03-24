# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculations.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Harshini y
#RegisterNumber:212223240050
import numpy as np
A=[[2,-3,0],[2,-5,0],[0,0,3]]
Eigenvalues,Eigenvectors=np.linalg.eig(A)
print("Eigen values are",Eigenvalues,"and Eigen Vectors are",Eigenvectors)
```
## Output:
![image](https://github.com/harshiniyu/EIGENVALUES-AND-EIGENVECTORS/assets/144979786/59304728-d366-4da8-b425-02db951d210d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
