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

## Register No:23013506
## Developed By:NITHISH KUMAR S

```Python

# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/nithish467/Norm-of-a-matrix/assets/150232274/c917515b-0234-4e35-a551-20cfe3b2a6c3)

### 2-Norm of a Matrix

![image](https://github.com/nithish467/Norm-of-a-matrix/assets/150232274/d5966288-75af-44ed-ac22-1a5a8331b9f2)


### Infinity Norm of a Matrix

![image](https://github.com/nithish467/Norm-of-a-matrix/assets/150232274/b72947f5-2197-4b2e-a153-f860b5bf1041)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
