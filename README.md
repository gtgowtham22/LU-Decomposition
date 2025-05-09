# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable
4.Print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: G.T.GOWTHAM
RegisterNumber: 24901330

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)



*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: G.T.GOWTHAM
RegisterNumber: 24901330

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)


*/
```

## Output:
![lu decomposition]()

![5-1](https://github.com/user-attachments/assets/e2083e13-5025-4947-b944-2f48069ac43e)

![5-2](https://github.com/user-attachments/assets/bf16b91e-9ed8-4df1-928c-479e8bb5ce40)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

