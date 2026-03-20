# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: LOGESH R
RegisterNumber: 212225040203

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
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
Program to find the LU Decomposition of a matrix.
Developed by: LOGESH R
RegisterNumber: 212225040203

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu,piv),b)
print(X)
*/
```

## Output:
![lu decomposition]()
<img width="1433" height="689" alt="image" src="https://github.com/user-attachments/assets/88e35cf4-fcdb-4560-9484-b0dc1488ad48" />
<img width="1234" height="592" alt="image" src="https://github.com/user-attachments/assets/92e4978d-33bd-4f8f-af97-0224894d6b69" />
<img width="1418" height="733" alt="image" src="https://github.com/user-attachments/assets/5c780fc6-cf14-4c9d-b5df-14c1d85cdf6e" />
<img width="1244" height="324" alt="image" src="https://github.com/user-attachments/assets/93e73fe2-c29a-42fb-b0c8-923831c5430d" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

