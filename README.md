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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Hariselvan
RegisterNumber: 212224040103
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-21 132532](https://github.com/user-attachments/assets/612a7218-965f-4f8b-a89f-16b6d10c8824)


### 2-Norm of a Matrix
![Screenshot 2025-04-21 132548](https://github.com/user-attachments/assets/b7009541-5760-4327-8c93-143bac245ebd)


### Infinity Norm of a Matrix
![Screenshot 2025-04-21 132603](https://github.com/user-attachments/assets/834fa986-2a3a-4af3-af2d-8bd51ea544c8)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
