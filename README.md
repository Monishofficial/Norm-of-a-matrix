## DATE:
## EXNO 07: Norm of a matrix
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
## 1-Norm of a Matrix
```
'''
Program to find the 1-Norm of a matrix and display the results in two decimal places.
Developed by : MONISH N
Register number: 212223240097
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)
```


## 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: MONISH N
RegisterNumber: 212223240097
'''

import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)
```



## Infinity Norm of a Matrix

```
'''
Program to find Infinity norm of a matrix.
Developed by: MONISH N
RegisterNumber: 212223240097
'''
import numpy as np
mat=np.array(eval(input()))

norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-10-23 220659](https://github.com/user-attachments/assets/b362bb1a-b08b-4a24-9bea-a5512adf2a11)

### 2-Norm of a Matrix
![Screenshot 2024-10-23 220807](https://github.com/user-attachments/assets/e7233dcf-1e54-4de7-b34c-70137b63dbcb)

### Infinity Norm of a Matrix
![Screenshot 2024-10-23 220829](https://github.com/user-attachments/assets/9cd7bda0-a50d-4b24-97fc-b8ed5baab2f3)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
