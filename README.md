# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Assemble the values for user.
### Step 2: 
Give the formula for the program.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
~~~
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print ("Eigen values are",values, "and Eigen Vectors are",vectors)
~~~
## Output:
![Eigen values](/values/git.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
