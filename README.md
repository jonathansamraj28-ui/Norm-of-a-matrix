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
# Register No:250132505
# Developed By:Jonathan samraj A
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans =np.linalg.norm(mat,1)
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
a="{:.2f}".format(ans)
print(a)
```
## Output:
### 1-Norm of a Matrix
<br><img width="1362" height="685" alt="image" src="https://github.com/user-attachments/assets/c3611e6d-af23-4262-ab00-f40525e2e382" />
<br>
<br>

### 2-Norm of a Matrix
<br><img width="1457" height="673" alt="image" src="https://github.com/user-attachments/assets/6136686e-c265-4e48-8927-681904542152" />
<br>
<br>

### Infinity Norm of a Matrix
<br><img width="1337" height="592" alt="image" src="https://github.com/user-attachments/assets/355fb332-c61c-4f34-ac1c-2ba618da9abd" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
