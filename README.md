# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1:
Get the input matrix using np.array()

Step 2:
Find the 2-norm of the matrix using np.linalg.norm()

Step 3:
Print the norm of the matrix in two decimal places.

Step 4:
End the program.
## Program:
```Python
# Register No: 212224230252
# Developed By: SANTHOSH V
# 1-Norm of a Matrix

'''Name : santhosh V
   Reg no: 212224230252
'''
import numpy as np

mat = np.array(eval(input("")))
ans = np.linalg.norm(mat, 1)
print("{:.2f}".format(ans))


#2-norm of a matrix
'''
Program to find 2-norm of a matrix.
name : santhosh V
reg no: 212224230252
'''

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 2)
print("{:.2f}".format(ans))

# Infinity Norm of a Matrix
'''
name : kannan R
reg no: 212224240072
'''
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))






```
## Output:
### 1-Norm of a Matrix
![{0F214B20-2FD4-4C83-B2D8-884AB918DC87}](https://github.com/user-attachments/assets/f6a168ae-1eaa-404e-b034-e80595422f16)


### 2-Norm of a Matrix
![{97A178ED-41DF-4C9D-A217-C62607A361BB}](https://github.com/user-attachments/assets/85c184b7-445e-4509-8c5d-2f0d4ee0555d)


### Infinity Norm of a Matrix
![{2853A67C-F8AE-4244-9871-E22D42EF4E99}](https://github.com/user-attachments/assets/d88cdf3f-1e7d-4c2b-93aa-9b1dfbb75ff7)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
