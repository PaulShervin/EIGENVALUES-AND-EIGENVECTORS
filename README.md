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
#Program to find the eigen values and eigen vectors.
#Developed by: paulshervinp
#RegisterNumber:24901141
import numpy as np
matrix=np.array([[2,2],[1,3]])
e_values,e_vectors= np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(e_values,e_vectors))

## Output:
![Screenshot 2024-11-17 161701](https://github.com/user-attachments/assets/3c665295-3a9b-4c3d-9ec3-d9ec423474c8)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
