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
# Register No: 212225230312
# Developed By: YOGESH A R
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input())) 
ans=np.linalg.norm(mat,2)
print(f"{ans:.2f}")


# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))  
n=np.linalg.norm(a,np.inf)
print(f"{n:.2f}")



```
## Output:
### 1-Norm of a Matrix
<br><img width="1093" height="798" alt="image" src="https://github.com/user-attachments/assets/783215f1-6f8c-4abf-843d-929fd986999d" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<br><img width="981" height="842" alt="image" src="https://github.com/user-attachments/assets/01da6a57-da17-46bb-9b0a-e567730f07b3" />

<br>

### Infinity Norm of a Matrix
<br>
<br><img width="1027" height="751" alt="image" src="https://github.com/user-attachments/assets/2cb8cfc1-4e20-4ec9-926a-37e48cc34950" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
