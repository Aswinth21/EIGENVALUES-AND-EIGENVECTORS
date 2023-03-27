# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np
### Step 2: 
Put the given values in the np.array command
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the program and get the output

## Program:
#Program to find the eigen values and eigen vectors.<br>
#Developed by: Aswinth T<br>
#RegisterNumber: 212222230015<br>
import numpy as np<br>
A = np.array([[2,2],[1,3]])<br>
values,vectors = np.linalg.eig(A)<br>
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))<br>
## Output:
![image](https://user-images.githubusercontent.com/120236638/227976130-4436c804-d6bf-4a75-9e77-9abea0c6b9d4.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
