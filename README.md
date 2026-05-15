# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = np.array([[2, -3, 0],
              [2, -5, 0],
              [0, 0, 3]])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
## Output:
<img width="1443" height="775" alt="image" src="https://github.com/user-attachments/assets/8470bf71-d9f4-4534-83e0-ee04376969bf" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
