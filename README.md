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
# Register No: M Parani Bala
# Developed By: 24900379
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
infinity_norm="{:.2f}".format(ans)
print(infinity_norm)
```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>

![Screenshot 2024-11-28 185514](https://github.com/user-attachments/assets/ecf49b3b-0103-4ded-8435-a0b62689f1e0)

### 2-Norm of a Matrix
<br>
<br>
<br>

![Screenshot 2024-11-28 185527](https://github.com/user-attachments/assets/d009b8a5-f6ce-48f7-ae0d-4bae54c8687d)


### Infinity Norm of a Matrix
<br>
<br>
<br>

![Screenshot 2024-11-28 185539](https://github.com/user-attachments/assets/cc372b94-4f54-489b-b5b1-94b7416ce85f)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
