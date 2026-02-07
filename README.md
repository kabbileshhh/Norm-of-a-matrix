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
# Register No:212225240063
# Developed By:KABBILESH.S
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

<img width="1435" height="864" alt="Screenshot 2026-02-07 090632" src="https://github.com/user-attachments/assets/d3115683-b48e-4198-99d2-b5c79eb4d148" />

### 2-Norm of a Matrix

<img width="1535" height="855" alt="Screenshot 2026-02-07 090650" src="https://github.com/user-attachments/assets/20da414f-8673-40d9-acff-128acdaf90d2" />
### Infinity Norm of a Matrix

<img width="1885" height="916" alt="Screenshot 2026-02-07 090739" src="https://github.com/user-attachments/assets/811a216e-7b45-4171-9379-6fa8bdc86204" />
## Result 

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
