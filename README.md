# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy.linalg import lu,lu_factor,lu_piv
3. Get input from the user as eval(input())
4. Use lu_factor and lu_solve to find LU decomposition
5. print L,U
6. print x

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: RAVIPRASATH K
RegisterNumber: 212224230225
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: RAVIPRASATH K
RegisterNumber: 212224230225
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:

![image](https://github.com/user-attachments/assets/301f0959-2254-4c63-8313-da0630a10803)

![image](https://github.com/user-attachments/assets/a0869c3d-b91b-4a4c-95df-447207045bbe)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

