# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy module to use the built-in-functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the matrix

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Aashika Jain .G
#RegisterNumber:24900589
import numpy as np
A=np.array([[2,2],[1,3]])
result1,result2=np.linalg.eig(A)
print("Eigen values are",result1,"and Eigen Vectors are",result2)
```

## Output:
![alt text](<Screenshot 2024-12-18 141758.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
