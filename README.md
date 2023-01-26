# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in functions for calculation
2.Prepare the lists from each linear equations and assign in np.array()
3.Using the lu() function in scipy.linalg module, we can find the solutions.
4.End the program
Program:

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: M.Jayachandran
RegisterNumber: 22008847
*/
```
```
import numpy as np  #from numpy import array
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: M.Jayachandran
RegisterNumber: 22008847
*/
```
```
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=eval(input())
A=np.array(arr)
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:

![landu](https://user-images.githubusercontent.com/118447015/212349912-29e8dd22-e290-44eb-8ded-c7d46a083ffb.png)

![lu](https://user-images.githubusercontent.com/118447015/212349944-ea856fbf-5d17-4dee-af02-07e768b9dd26.png)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

