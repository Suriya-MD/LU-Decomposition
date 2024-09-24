## Date:
# Exp-05 LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy extension and scipy.linalg extension
2. Initialize the matix values
3. Use lu functions from imported extensions
4. Print the output

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
/*
Program to find the L and U matrix.
Developed by: SURIYA M
RegisterNumber: 212223110055
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
/*
Program to find the LU Decomposition of a matrix.
Developed by: SURIYA M
RegisterNumber: 212223110055
*/
```

## Output:
![lu decomposition]()

![image](https://github.com/user-attachments/assets/f52d9a0c-ac4c-41ab-9fab-ba5a387c65fc)

![image](https://github.com/user-attachments/assets/0c2f9868-5cb7-4f25-acad-891077ccc934)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

