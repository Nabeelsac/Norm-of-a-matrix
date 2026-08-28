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
# Register No: 212225220005
# Developed By: AJAYPRABU.A

# 1-Norm of a Matrix
```import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```




# 2-Norm of a Matrix
```

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```




# Infinity Norm of a Matrix
```
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
<img width="722" height="247" alt="image" src="https://github.com/user-attachments/assets/5397ee7e-a0c2-49b5-9e59-3a0e681c2c89" />


### 2-Norm of a Matrix
<img width="727" height="282" alt="image" src="https://github.com/user-attachments/assets/49dfbc39-ff22-4079-9862-5f25cc6f43a6" />

### Infinity Norm of a Matrix
<img width="702" height="192" alt="image" src="https://github.com/user-attachments/assets/737ac6a8-0c73-4cf6-bac2-3db282e9275b" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
