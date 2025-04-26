# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.  print the variable 'X


## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu

# Input matrix from user
A = np.array(eval(input()))

# Perform LU decomposition
P, L, U = lu(A)

# Output L and U matrices
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by:Harshavardhan.K.B
RegisterNumber:212224240054
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
/*
Program to find the LU Decomposition of a matrix.
Developed by:Harshavardhan.K.B 
RegisterNumber:1224240054
*/
```


## Output:
![Screenshot 2025-04-26 114133](https://github.com/user-attachments/assets/041de177-4165-40d1-9a19-cd56d0ee2366)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

