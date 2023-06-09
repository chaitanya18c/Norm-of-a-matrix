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
# Register No: 212222230024
# Developed By: CHAITANYA P S
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
n=np.linalg.norm(a,1)
print("{:.2f}".format(n))

# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
n=np.linalg.norm(a,2)
print("{:.2f}".format(n))

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
n=np.linalg.norm(a,np.inf)
print("{:.2f}".format(n))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/chaitanya18c/Norm-of-a-matrix/assets/119392724/c9d86650-94ec-4537-bd00-1fe514e24293)

### 2-Norm of a Matrix
![image](https://github.com/chaitanya18c/Norm-of-a-matrix/assets/119392724/701aa58e-3fa6-43f3-a947-fc83e9398c11)

### Infinity Norm of a Matrix
![image](https://github.com/chaitanya18c/Norm-of-a-matrix/assets/119392724/57378e57-2354-43c6-a136-2833f77a8e80)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
