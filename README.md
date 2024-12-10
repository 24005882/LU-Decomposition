# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner


## Algorithm
## Program 1
1. Import numpy library.
2. Import lu function from scipy library.
3. Solve LU decomposition using lu_solve() function.
4. print the value.
## Program 2
1. import numpy
2. From scipy.linalg import lu ,lu_factor,lu_solve respectively
3. Get the input of matrix values from user using eval 
4. Print and solve LU decomposition using lu_solve() function.

## Program:
(i) To find the L and U matrix
```python
#Program to find the L and U matrix.
#Developed by: THARUN M
#RegisterNumber: 24005882
import numpy as np 
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
#Program to find the LU Decomposition of a matrix.
#Developed by: THARUN M
#RegisterNumber: 24005882
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)
```

## Output:

![Screenshot 2024-12-10 134945](https://github.com/user-attachments/assets/80f1ca7b-e932-4ad2-8981-5d12e30e61af)

![Screenshot 2024-12-10 134954](https://github.com/user-attachments/assets/8966242f-b389-4758-80e3-2d97678d50b4)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

