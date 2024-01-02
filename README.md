# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import the required libraries
### Step 2: 
define a matrix A
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
display the calculus eigen values and eigen vectors
## Program:
```
import numpy as np
a=[[2,-3,0],[2,-5,0],[0,0,3]]
value,vectors=np.linalg.eig(a)
print("Eigen values are",value,"and Eigen Vectors are",vectors)
```
## Output:
![image](https://github.com/Harishragaventhira/EIGENVALUES-AND-EIGENVECTORS/assets/145548269/d4e13e32-47f2-452f-b01b-fdae266a3702)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
