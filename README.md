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
Program to find the L and U matrix.
Developed by: R.Bharathi Shankar
RegisterNumber: 212225230032
*/

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: R.Bharathi Shankar
RegisterNumber: 212225230032
*/

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
![lu decomposition]()

<img width="1184" height="848" alt="Screenshot 2026-03-24 161752" src="https://github.com/user-attachments/assets/468b9060-e924-4b00-854b-bfa33fd93b24" />


<img width="1135" height="773" alt="Screenshot 2026-03-24 161815" src="https://github.com/user-attachments/assets/e6eaf401-740b-4ad5-a5fc-989914b597f5" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

