# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :

Import the numpy module to use the built-in functions for calculation

Step 2:

Get the input matrix from the user

Step 3:

Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:

End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: PERARASU M
#RegisterNumber: 212222100033

import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```

## Output:
![Screenshot 2023-03-20 105344](https://user-images.githubusercontent.com/118348589/226253830-125528f4-b429-435a-8f88-d4c614aad173.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
