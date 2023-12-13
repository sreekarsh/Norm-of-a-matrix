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
# Developed By:Masina Sree Karsh
# Register No: 23005860
# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
nom="{:.2f}".format(ans)
print(nom)



# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
nom="{:.2f}".format(ans)
print(nom)


# Infinity Norm of a Matrix


import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
nom="{:.2f}".format(ans)
print(nom)

```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/sreekarsh/Norm-of-a-matrix/assets/139841918/16926f35-f5f3-4e3e-8428-8f373d8be038)


### 2-Norm of a Matrix

![image](https://github.com/sreekarsh/Norm-of-a-matrix/assets/139841918/6681393e-f69a-4175-bd6a-3aac1147d021)


### 3-Infinity Norm of a Matrix

![image](https://github.com/sreekarsh/Norm-of-a-matrix/assets/139841918/ed64b43b-e463-4eed-9dbf-4f4edf3e811a)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
