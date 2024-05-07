# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.print the variable 'X'

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Sabarinath.R
RegisterNumber: 212223100048
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Sabarinath.R
RegisterNumber: 212223100048
'''

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
![Screenshot 2024-05-07 144450](https://github.com/Sabari-2005/LU-Decomposition/assets/139338709/ddf15301-4a04-44d4-95fe-fe9716a943ab)
![Screenshot 2024-05-07 144459](https://github.com/Sabari-2005/LU-Decomposition/assets/139338709/85b3e3dc-96f1-4363-86c7-61bef13eaae9)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

