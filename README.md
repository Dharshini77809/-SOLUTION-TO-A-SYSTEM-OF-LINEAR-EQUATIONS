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
import numpy as np
a=np.array([[1,-3],[3,1]])
b=np.array([0,10])
x=np.linalg.solve(a,b)
print(x)
#Developed by: S.PRIYADHARSHINI
#RegisterNumber: 25017590
```

## Output:
<img width="1250" height="710" alt="Screenshot 2026-02-08 124842" src="https://github.com/user-attachments/assets/94c3b793-d03b-46c8-b745-32b2e064f4f9" />
<img width="1325" height="396" alt="Screenshot 2026-02-08 171517" src="https://github.com/user-attachments/assets/0523d2af-c148-4e27-a137-d902fcb33bfb" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

