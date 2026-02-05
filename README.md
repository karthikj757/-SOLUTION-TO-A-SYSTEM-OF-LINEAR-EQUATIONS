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
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
x=np.linalg.solve(A,B)
print(x)
```

## Output:

<img width="848" height="422" alt="Screenshot 2026-02-05 082954" src="https://github.com/user-attachments/assets/0e8509bb-d650-477c-9501-2837654b6fc8" />
<img width="857" height="288" alt="Screenshot 2026-02-05 083010" src="https://github.com/user-attachments/assets/ca3528b0-72b0-413c-9c99-174c4bc1e5c6" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

