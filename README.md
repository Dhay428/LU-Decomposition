# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
i)

find the 1 and u matirx by using numpy and linalg from scipy

print the 1 matrix and u matirx

find the lu decomposition by using numpy and lu_factor and lu_solve

print the the following  matrix

ii)

In second program can import lo factor and lu selve from python library as same as in second program.

Get the input from user in the form of nested list to compute numpy array format and declare it for both the variables

Step Create the variable to Use inputted array to compute of lu, factor of matrix varaible.

Step Create the new variable for a solve to compute of x variable and b' variable.

Steps Print the corresponding variable (solution) to get the output

## Program:
(i) To find the L and U matrix
```
'''Program to find the L and U matrix using LU decomposition.
Developed by: S.Dhayalaprabu
RegisterNumber:24006289
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to find the LU Decomposition of a matrix.
Developed by: S.Dhayalaprabu
RegisterNumber: 24006289
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```

## Output:
![Screenshot 2024-12-12 223859](https://github.com/user-attachments/assets/3e01d645-d92a-4b7e-96da-81f3279bb797)

![Screenshot 2024-12-12 223916](https://github.com/user-attachments/assets/8c4bbff1-1f68-4b87-93cc-1cd83a702972)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

