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
	4. End the program
## Program:
```Python
# Register No: 24900445
# Developed By: Kiruba RC
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
result="{:.2f}".format(ans)
print(result)




# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
result="{:.2f}".format(ans)
print(result)




# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
res="{:.2f}".format(ans)
print(res)




```
## Output:
### 1-Norm of a Matrix
![screenshot text](<Screenshot 2024-12-08 160037.png>)
<br>
<br>
<br>

### 2-Norm of a Matrix
![screenshot text](<Screenshot 2024-12-08 160045.png>)
<br>
<br>
<br>

### Infinity Norm of a Matrix
![screenshot text](<Screenshot 2024-12-08 160052.png>)
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
