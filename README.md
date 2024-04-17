
# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import lu(),lu_factor() and lu_solve() from scipy.linalg library
2. Use lu() method to find lower and upper matrix.
3. Use lu_factor() and lu_solve to solve the two matrixes.
4. End the program.

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Karthikeyan P
RegisterNumber: 212223230102
```
```
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,lower_matrix,upper_matrix=lu(matrix)
print(lower_matrix)
print(upper_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Karthikeyan P
RegisterNumber: 212223230102
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```
## Output:
### (i) L and U
![Screenshot 2024-04-17 112724](https://github.com/karthikeyanpachiyappan/LU-Decomposition/assets/155143878/f7d3b45a-d8cb-4b6e-b76a-a8a9ef39f97c)

### (ii) LU decomposition
![Screenshot 2024-04-17 112754](https://github.com/karthikeyanpachiyappan/LU-Decomposition/assets/155143878/6ac4c36d-d591-4e6f-818b-15823c5ab518)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

