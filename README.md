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

# 1-Norm of a Matrix
'''
Developed by: Lohini S
Register number: 25015038
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Lohini S
RegisterNumber: 25015038
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))



# Infinity Norm of a Matrix

'''
Program to find the infinity of a matrix
Developed by: Lohini S
Register number: 25015038
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix

<img width="1162" height="848" alt="Screenshot 2026-02-08 133603" src="https://github.com/user-attachments/assets/1a5d2676-d2a5-4c97-9a10-49b8078687e0" />


### 2-Norm of a Matrix

<img width="1237" height="883" alt="Screenshot 2026-02-08 133627" src="https://github.com/user-attachments/assets/be4b65e9-fd43-412b-b1ce-3b287b59c4d2" />


### Infinity Norm of a Matrix

<img width="1326" height="865" alt="image" src="https://github.com/user-attachments/assets/8dfc6c28-463e-435d-b7ca-a405823c3ad3" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
