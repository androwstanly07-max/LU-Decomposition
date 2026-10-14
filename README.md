# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

#5.a.
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the scipy.linalg.lu(), we can find the solutions.
4. End the program

#5.b
1.  Import the numpy module to use the built-in functions for calculation
2.  Prepare the lists from each linear equations and assign in np.array()
3.  Using the scipy.linalg.lu(), we can find the solutions.
4.  Use the lu_factor() function to obtain the LU factorization of A matrix
5.  use the lu_solve() function to solve the system of linear equation
6.  End the program 
 

## Program:
(i) To find the L and U matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```

## Output:
![lu decomposition]()
<img width="1373" height="785" alt="Screenshot 2026-10-14 091153" src="https://github.com/user-attachments/assets/1cd5fb70-caf9-463d-9338-c505acc5f126" />
<img width="1374" height="601" alt="Screenshot 2026-10-14 091214" src="https://github.com/user-attachments/assets/fab4ae44-c5e0-4a84-bb67-64d02d8abcc6" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

