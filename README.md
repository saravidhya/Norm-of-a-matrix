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
# Register No: 212223230238
# Developed By: VIDHIYA LAKSHMI S
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
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

![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/87062069/94c4e733-1de3-4c79-9291-327998512a8e)

### 2-Norm of a Matrix

![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/87062069/8e474517-c932-48bc-9125-84d12ae9e807)


### Infinity Norm of a Matrix

![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/87062069/ed0f7409-fc98-476e-a3a1-a4040e3855bb)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
