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
# Register No: 23000033
# Developed By: ADITHYA V

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/ADITHYA23000033/Norm-of-a-matrix/assets/148514544/9d8cf929-c6b2-4b14-8eb7-e5c08e72836c)

### 2-Norm of a Matrix

![image](https://github.com/ADITHYA23000033/Norm-of-a-matrix/assets/148514544/298cb805-b801-4d21-ba42-02d8817adcef)

### Infinity Norm of a Matrix

![image](https://github.com/ADITHYA23000033/Norm-of-a-matrix/assets/148514544/c0745441-8f98-45a9-b3c0-c17aa27c8c9b)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
