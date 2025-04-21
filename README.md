# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy moduke to use the build-in functions for calculations

Step 2:
Prepare the list for each linear equation and assign in np.array()

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program
## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Kesav KM
#RegisterNumber:212224110031
import numpy as np
A = np.array([[2, 2],
              [1, 3]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues,end=" and ")
print("Eigen Vectors are", eigenvectors,end="")



## Output:

![Screenshot 2025-03-27 210433](https://github.com/user-attachments/assets/36aa0bbc-7415-45fa-b2dd-57b26528c699)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
