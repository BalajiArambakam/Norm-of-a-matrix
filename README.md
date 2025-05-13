# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Get the input matrix using np.array()   
### Step 2:
Find the 2-norm of the matrix using np.linalg.norm()
### Step 3:
Print the norm of the matrix in two decimal places.
### Step 4:
End the program.
## Program:
```
'''
Program to find 2-norm of a matrix.
Developed by: BALAJI ARAMBAKAM
RegisterNumber: 212224230021
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# 2-Norm of a Matrix
``
'''
Program to find 2-norm of a matrix.
Developed by: BALAJI ARAMBAKAM
RegisterNumber: 212224230021
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: TITUS RATNA KUMAR KARIVELLA
RegisterNumber: 212224230292
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/893aa7c4-f2cf-45b8-8b51-03621245c215)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/901a46d7-3be6-408c-b520-de2a1d1b5d6b)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/d1fe704a-e491-4a12-be01-2135d65e5386)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
