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
<br>![Screenshot 2024-11-28 185514](https://github.com/user-attachments/assets/9bef925f-57a3-4c43-a167-3ec1b729d494)


### 2-Norm of a Matrix
<br>
<br>
<br>![Screenshot 2024-11-28 185527](https://github.com/user-attachments/assets/61f9eeb3-d95d-434c-9822-b03411e9f0ee)


### Infinity Norm of a Matrix
<br>
<br>
<br>![Screenshot 2024-11-28 185539](https://github.com/user-attachments/assets/1b5898ff-3611-41af-af77-6d6f05e496bb)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
