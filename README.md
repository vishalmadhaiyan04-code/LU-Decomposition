# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2. Import the required NumPy library.
3. Define the given square matrix A.
4. Initialize lower triangular matrix L and upper triangular matrix U with zeros.
5. Compute the elements of U matrix using LU decomposition formula.
6. Compute the elements of L matrix.
7. Display the L matrix and U matrix.
8. Stop the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 212225240186
RegisterNumber: VISHAL M

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
from scipy.linalg import lu

A = np.array(eval(input()), dtype=float)

P, L, U = lu(A)

print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 212225240186
RegisterNumber: VISHAL M

os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
from scipy.linalg import lu

A = np.array(eval(input()), dtype=float)
B = np.array(eval(input()), dtype=float)

P, L, U = lu(A)

Y = np.linalg.solve(L, np.dot(P, B))
X = np.linalg.solve(U, Y)

print(X)


*/
```

## Output:

<img width="1358" height="474" alt="image" src="https://github.com/user-attachments/assets/25147fab-de43-4039-99d0-217096282964" />

<img width="1266" height="246" alt="image" src="https://github.com/user-attachments/assets/567ce38d-8da7-4ec3-a9e0-adbed73eb220" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

