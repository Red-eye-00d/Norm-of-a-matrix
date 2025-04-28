# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 212224230276
# Developed By: SUDHARSANAN U

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
normofmatrix = "{:.2f}".format(ans)
print(normofmatrix)

Program to find 2-norm of a matrix.
Developed by: SUDHARSANAN U 
RegisterNumber: 212224230276

```
## Output:
### 1-Norm of a Matrix

<br>![image](https://github.com/user-attachments/assets/34a37310-c0e6-4c10-9f68-477b3eee5ed5)

<br>

### 2-Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/bfaff86f-fc69-4776-b53a-61bafa767c41)

<br>
<br>

### Infinity Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/aa13eefb-b17a-4c40-a8b9-59f3badada97)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
