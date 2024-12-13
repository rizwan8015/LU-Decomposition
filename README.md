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
/*
'''Program to find L and U matrix using LU decomposition.
Developed by:rizwan 
RegisterNumber: 24900277
'''
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
'''Program to solve a matrix using LU decomposition.
Developed by: rizwan
RegisterNumber:24900277 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu,lu_solve,lu_factor
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x) 
*/
```

## Output:
![Screenshot 2024-12-13 095246](https://github.com/user-attachments/assets/88f0c5db-ca2b-41e8-bc47-17b40e03de78)
![Screenshot 2024-12-13 095256](https://github.com/user-attachments/assets/931075d3-b591-4bb8-ad6c-ec8b512baa72)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

