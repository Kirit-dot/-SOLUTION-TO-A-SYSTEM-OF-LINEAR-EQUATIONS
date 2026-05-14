# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
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
#Program to find the solution for the given linear equations.
#Developed by: KIRIT LULLA
#RegisterNumber: 212225230139
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,-3],[3,1]])
b=np.array([0,10])
le=np.linalg.solve(a,b)
print(le)
```

## Output:
<img width="391" height="203" alt="Screenshot 2026-05-14 140354" src="https://github.com/user-attachments/assets/721958de-504d-4b2e-ab4a-6604e50b3aa1" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

