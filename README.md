# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
 
## Program:
```
import numpy as np
A= np.array([[3,2,5], [1,1,2],[3,3,6]])
X= np.linalg.matrix_rank(A)
print (X)
```
## Output:

<img width="1920" height="1080" alt="Screenshot 2025-11-24 203729" src="https://github.com/user-attachments/assets/ab0d00ed-c569-4511-8080-8b7ace7e41d6" />
<img width="1920" height="1080" alt="Screenshot 2025-11-24 203744" src="https://github.com/user-attachments/assets/b0f36b9e-ceb1-408a-8010-e7932f2f0f07" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

