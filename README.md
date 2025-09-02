# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: IRSHATH AHAMED.N
RegisterNumber: 212224110025
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
'''Program to solve a matrix using LU decomposition.
Developed by: IRSHATH AHAMED.N
RegisterNumber: 212224110025
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)

```

## Output:

<img width="1307" height="962" alt="PLA 5A output" src="https://github.com/user-attachments/assets/ea5a8bc1-8d3a-4f77-8e9a-7a4086994a7d" />
<img width="1286" height="957" alt="pla 5b output" src="https://github.com/user-attachments/assets/5d588011-df6a-4757-9e7f-551b696bee1c" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

