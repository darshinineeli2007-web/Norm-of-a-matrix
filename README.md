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
```
```Python
# Register No:212225230200
# Developed By:Neeli darshini
```
# 1-Norm of a Matrix
import os
os.environ['OPENBLAS_NUM_THREADS']="1"
import numpy as np
A=np.array(eval(input()))
normal=np.linalg.norm(A,1)
print(normal)
# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")
# Infinity Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norminf=np.linalg.norm(A,np.inf)
print(f"{norminf:.2f}")
```
```
### Output:
### 1-Norm of a Matrix
<img width="438" height="153" alt="image" src="https://github.com/user-attachments/assets/0a1f0187-db97-4441-814d-ae396f301a42" />

### 2-Norm of a Matrix
<img width="392" height="188" alt="image" src="https://github.com/user-attachments/assets/caeaed74-0138-4518-80ab-702b4a90176b" />

### Infinity Norm of a Matrix
<img width="443" height="156" alt="image" src="https://github.com/user-attachments/assets/c2a70664-0a61-4d2e-b656-8a3dfae6f8f7" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
