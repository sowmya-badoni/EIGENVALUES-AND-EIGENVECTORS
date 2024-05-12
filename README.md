# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : 

Import the numpy module to use the built-in functions for calculation.

### Step 2: 

Prepare the lists from each equations and assign in np.array()

### Step 3:

Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 

End the program

## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by: SOWMYA BADONI
#RegisterNumber: 212223230211
import numpy as np
A = np.array([[2, 2], [1, 3]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(eigenvalues,eigenvectors))
```

## Output:
![Screenshot 2024-05-12 174108](https://github.com/sowmya-badoni/EIGENVALUES-AND-EIGENVECTORS/assets/152136324/e24370c5-ea90-4162-abc8-ea63c84a30f5)


## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program

