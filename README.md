# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm, and infinity norm of the matrix and display the result in two decimal places.
## Equipment required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## STEP 1:
Get the input matrix using np.array()
## STEP 2:
Find the matrix's 2-norm,1-norm, and infinity norm using np.linalg.norm()
## STEP 3:
Print the norm of the matrix in two decimal places.
## STEP 4:
End of program

## Program:
## 1-Norm of a Matrix
```
'''
program to find the 1-Norm of a matrix 
Developed by: SREEKUMAR S
register number: 23008070
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
norm="{:.2f}".format(result)
print(norm)
```
# 2-Norm of a Matrix
```
'''
program to find the 2-Norm of a matrix 
Developed by: SREEKUMAR S
register number: 23008070
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
norm="{:.2f}".format(result)
print(norm)

```




# Infinity Norm of a Matrix
```
'''
program to find the Infinity of a matrix 
Developed by: SREEKUMAR S
register number: 23008070
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
norm="{:.2f}".format(result)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![norm 1](https://github.com/guru14789/Norm-of-a-matrix/assets/151705853/7fece0a8-5a43-4269-955b-640a0118666f)


### 2-Norm of a Matrix
![norm 2](https://github.com/guru14789/Norm-of-a-matrix/assets/151705853/dc4addbb-f9af-4edf-a2bf-bfc5e6a62833)


### Infinity Norm of a Matrix
![norm inf](https://github.com/guru14789/Norm-of-a-matrix/assets/151705853/53612f1a-aef4-485d-bee8-daa2f7078f44)


## Result
Thus the program for the 1-norm, 2-norm, and Infinity norm of a matrix are written and verified.
