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
# Register No:212221243001
# Developed By:Balaji J
# 1-Norm of a Matrix
'''
program to find 1-norm of a matrix.
Developed by:Balaji J
Register number:212221243001
'''
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))
```


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Balaji J
RegisterNumber: 212221243001
'''
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))
```

# Infinity Norm of a Matrix

'''
Program to find Infinity-norm of a matrix.
Developed by: Balaji J
RegisterNumber: 212221243001
'''
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))



```
## Output:
### 1-Norm of a Matrix

![m8](https://github.com/Balaji-Jothiramalingam/Norm-of-a-matrix/assets/114234865/3ad29803-6afa-4e2c-81b4-a44ac87ef766)


### 2-Norm of a Matrix


![m9](https://github.com/Balaji-Jothiramalingam/Norm-of-a-matrix/assets/114234865/c8c599dc-a7dc-4347-88d5-d73f5b1738a6)


### Infinity Norm of a Matrix

![m10](https://github.com/Balaji-Jothiramalingam/Norm-of-a-matrix/assets/114234865/1a2afe35-17af-47ed-a874-05fcd4e701ab)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
