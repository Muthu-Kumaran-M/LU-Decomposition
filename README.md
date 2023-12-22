# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linald import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Muthu Kumaran M
RegisterNumber:23006606
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Muthu Kumaran M
RegisterNumber:23006606
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
![Exp 5 1](https://github.com/Muthu-Kumaran-M/LU-Decomposition/assets/144979439/ba13a88c-bbb1-45bb-ace0-776e74f2d365)
![Exp 5 2](https://github.com/Muthu-Kumaran-M/LU-Decomposition/assets/144979439/e0e63004-a6fc-49b4-b4a4-7da4aa3b25b6)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

