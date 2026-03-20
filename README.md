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
```
# Register No:
# Developed By:

```
# 1-Norm of a Matrix

```python

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


# 2-Norm of a Matrix

```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))

```


# Infinity Norm of a Matrix
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))


```
## Output:
### 1-Norm of a Matrix
<br>![7 a mfai](https://github.com/user-attachments/assets/c9225de2-d554-4088-8fc6-fee624326861)

<br>
<br>

### 2-Norm of a Matrix
<br>![7 b mfai](https://github.com/user-attachments/assets/1f793f08-b91b-499e-90b6-56023831107b)

<br>
<br>

### Infinity Norm of a Matrix
<br>![7 c mfai](https://github.com/user-attachments/assets/0aec6afa-1bcc-421a-996c-88c7805f98d2)

<br>  
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
