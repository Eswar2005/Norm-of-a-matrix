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
/*
Register No:22008747
Developed By:Adhithyha Perumal.D
*/
```
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)
```

# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)
```

## Output:
### 1-Norm of a Matrix
![norm](https://user-images.githubusercontent.com/121166390/215309936-0cdc8624-94f0-4442-b177-f592610ee303.png)

### 2-Norm of a Matrix
![norm 2](https://user-images.githubusercontent.com/121166390/215310001-67f8dc68-8c04-4283-9324-6e201baa8af7.png)

### Infinity Norm of a Matrix
![norm 3](https://user-images.githubusercontent.com/121166390/215310056-42cfdf28-eba7-40e8-bae8-edf2ef33c755.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
