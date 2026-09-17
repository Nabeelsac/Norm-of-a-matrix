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
# Register No: 212224100040
# Developed By: Nather Nabeel S A C
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```


## Output:
### 1-Norm of a Matrix

<img width="1286" height="890" alt="image" src="https://github.com/user-attachments/assets/715e8fc4-6e96-4951-92af-95236c1061ec" />



### 2-Norm of a Matrix

<img width="1281" height="857" alt="image" src="https://github.com/user-attachments/assets/47af80a0-9333-470d-9027-ad4fa1e6b47d" />


### Infinity Norm of a Matrix

<img width="1407" height="957" alt="image" src="https://github.com/user-attachments/assets/de08bd70-e470-471b-abbf-60eee5bc3195" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
