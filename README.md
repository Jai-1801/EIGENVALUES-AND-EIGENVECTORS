# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
we have to initialise program using import numpy to perform mathematical calculation
### Step 2: 
The input from the user is stored in the variable A
### Step 3: 
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End of the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Jai Surya
#RegisterNumber: 23002572

import numpy as np
A = np.array([[2,2],[1,3]])
values,vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

```
## Output:
![OutPut](/OUTPUT.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
