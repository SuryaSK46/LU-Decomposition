# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Get the input matrix from user

2.write a program to find the L and U matrix

3.using the L and U matrix slove the matrix

4.display the output

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Surya S K
RegisterNumber: 212222100052
'''
import  numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Surya SK
RegisterNumber: 212222100052
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array(eval(input()))
B=np.array(eval(input()))
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)

```

## Output:
(i) To find the L and U matrix
![Screenshot 2023-06-10 024224](https://github.com/SuryaSK46/LU-Decomposition/assets/127716537/bb1007d5-a741-46b3-8851-0e610a163f41)
(ii) To find the LU Decomposition of a matrix
![Screenshot 2023-06-10 024339](https://github.com/SuryaSK46/LU-Decomposition/assets/127716537/185bbd7a-5798-4d72-abd6-b19671389359)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

