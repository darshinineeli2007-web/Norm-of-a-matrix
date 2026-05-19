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
## Output:
### 1-Norm of a Matrix
<img width="852" height="347" alt="image" src="https://github.com/user-attachments/assets/3d9c2c81-ce4b-4124-8a4e-0c1ef961ccef" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="1047" height="390" alt="image" src="https://github.com/user-attachments/assets/8de80454-b482-49a1-ae1b-03f84af22e93" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="982" height="341" alt="image" src="https://github.com/user-attachments/assets/021566b0-e620-41ea-be25-aed1a69d5304" />

<br>
<br>
<br>

## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
