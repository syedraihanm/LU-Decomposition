# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. find the l and u matirx by using numpy and linalg from scipy
2. print the l matrix and u matirx
3. find the lu decomposition by using numpy and lu_factor and lu_solve
4. print the the following matrix

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
/*
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```

## Output:

![image](https://github.com/user-attachments/assets/50bb0287-e3dc-40f9-86a1-f082f6ef518c)

![image](https://github.com/user-attachments/assets/ac00408a-b47a-4b93-ba39-a525e59ad7e2)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

