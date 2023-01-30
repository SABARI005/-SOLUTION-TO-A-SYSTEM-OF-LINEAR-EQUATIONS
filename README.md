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
Solving System of linear equations
#developed by :SABARI.S
#REGISTER NO :22008698
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
result=np.linalg.solve(A,B)
print(result)
```
##  Output:
![209549050-9ff27675-2173-4d3d-84fd-1308b90d3375](https://user-images.githubusercontent.com/118660461/215513375-90ab5947-41a4-4355-a6be-1613da091107.png)
 Output:

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

