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
# Register No:23004952
# Developed By:Sriram R
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))


# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))


# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))


```
## Output:
### 1-Norm of a Matrix
![output](https://github.com/Rsriram13/Norm-of-a-matrix/assets/145742823/d2671177-d2f1-4c2a-82e3-703dce082a93)

### 2-Norm of a Matrix
![output](https://github.com/Rsriram13/Norm-of-a-matrix/assets/145742823/c9df231e-9d6b-4dab-b5dd-089157378848)

### Infinity Norm of a Matrix
![output](https://github.com/Rsriram13/Norm-of-a-matrix/assets/145742823/60484954-4d6a-4193-83c4-9c008230fc59)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
