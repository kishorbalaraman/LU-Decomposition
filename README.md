# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Step 1:Import the numpy module to use the built-in functions for calculation

Step 2:Prepare the lists from each linear equations and assign in np.array()

Step 3:Using the np.linalg.solve(), we can find the solutions.

Step 4:End the program


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
'''
'''Program to find L and U matrix using LU decomposition.
Developed by: B.kishor
RegisterNumber: 
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=eval(input())
p,l,u=lu(A)
print(l)
print(u)

'''
Developed by: KISHOR.B
RegisterNumber:212225230141 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
...
'''Program to solve a matrix using LU decomposition.
Developed by: B Kishor
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=eval(input())
piv,lu=lu_factor(A)
result=lu_solve((piv,lu),b)
print(result)
...
Developed by: KISHOR.B
RegisterNumber: 212225230141
*/
```

## Output:
![lu decomposition]()
<img width="928" height="722" alt="Screenshot 2026-03-30 210100" src="https://github.com/user-attachments/assets/c1242c19-ea33-4f23-a630-3f700dea286f" />

<img width="777" height="601" alt="Screenshot 2026-03-30 210134" src="https://github.com/user-attachments/assets/1dbb0b67-c064-43f3-aee5-9ab755cef90f" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

