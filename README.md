<img width="1920" height="1080" alt="Screenshot (103)" src="https://github.com/user-attachments/assets/8d021d3b-5125-4caf-9b71-b2a78eb2b167" /># LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
step1:
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using the np.linalg.solve(), we can find the solutions.

Step 4:
End the program
## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
 import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot= lu_factor(A)
x=lu_solve((lu,pivot), B)
print(x)

```

## Output:

<img width="1920" height="1080" alt="Screenshot (103)" src="https://github.com/user-attachments/assets/efc6357e-ef0b-47fe-8b37-dd980fd5be97" />

<img width="1920" height="1080" alt="Screenshot (104)" src="https://github.com/user-attachments/assets/ffddbf1c-0647-484e-9b33-5ab5325325ff" />

<img width="1920" height="1080" alt="Screenshot (105)" src="https://github.com/user-attachments/assets/cb01ec39-ea0d-49b9-9b97-f125267b0011" />

<img width="1920" height="1080" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/6689464b-b68c-4527-9cb8-a3098a427fd7" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

