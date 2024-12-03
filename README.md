# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy
### Step 2: use np.linalg
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: end the program

## Program:



import numpy as np

# Given matrix
A = np.array([[-2, 2, -3], [2, 1, -6], [-1, -2, 0]])

# Find the eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(A)

# Print eigenvalues and eigenvectors on the same line
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")





## Output:
![Screenshot 2024-12-03 100925](https://github.com/user-attachments/assets/766bcbe6-d549-4763-bfe7-c16671062a53)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
