# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X

## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by: M BALASURIYA
RegisterNumber: 212224240021
'''

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
p,l,u = lu(A)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by: M BALASURIYA
RegisterNumber: 212224240021
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
l,p = lu_factor(a)
x = lu_solve((l,p),b)
print(x)
```

## Output:
<img width="860" height="974" alt="image" src="https://github.com/user-attachments/assets/2a0bb4d8-0c4b-4e31-bc8e-c2bb6ad16533" />
<img width="641" height="806" alt="image" src="https://github.com/user-attachments/assets/2bd9a081-5a03-404e-b7b6-866715030f8c" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

