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
#Developed by: P.V.Abishek
#RegisterNumber:212222230003
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
result=np.linalg.solve(A,B)
print(result)
```
## Output:
![Screenshot 2023-06-03 122859](https://github.com/pvabishek/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/119405626/8c02124f-dda3-4878-a8f2-38e36a5ccad8)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

