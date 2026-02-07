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
'''
Developed by : ABHISHEK S
Register Number: 212225100001
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname
RegisterNumber: 
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))



# Infinity Norm of a Matrix
'''
Program to find the infinity of a matrix
Developed by: ABHISHEK S
Register Number: 212225100001
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/43c9edb0-90ee-4210-bbd1-9412949eb897" />


### 2-Norm of a Matrix
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/b51ad9e4-8313-4890-b139-f96c41fdb740" />


### Infinity Norm of a Matrix
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/f8333925-c3da-4623-817b-e938fffb0946" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
