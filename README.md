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
#Developed by: PRAVEEN V
#RegisterNumber:23013808
import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
soln=np.linalg.solve(a,b)
print(soln)
```
## Output:
![Screenshot 2023-11-16 232108](https://github.com/praveenv23013808/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/145824728/0697428b-2b30-49f2-977e-ec2c60ea3250)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

