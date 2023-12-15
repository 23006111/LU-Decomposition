# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
 

## Program:
(i) To find the L and U matrix
```
Developed by:RAMYA P 
RegisterNumber: 23006111
import numpy as np
from scipy.linalg import lu

A=np.array(eval(input()))
P,L,U= lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Developed by:RAMYA P 
RegisterNumber:23006111 
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
![image](https://github.com/23006111/LU-Decomposition/assets/145981696/38f5a8a4-bc76-4346-a26a-0df307f7a0bd)
![image](https://github.com/23006111/LU-Decomposition/assets/145981696/7111e3d2-1815-4471-b40f-ffc0e55ba181)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

