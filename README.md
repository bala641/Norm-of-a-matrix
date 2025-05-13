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
# Register No:212224100005
# Developed By:BALA B

# 1-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)

# 2-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print(f"{result:.2f}")

# Infinity Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print(f"{result:.2f}")
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/514abbaa-5822-4dfc-9ec0-9e09909d875e)




### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/ece3c86a-6202-4627-8970-481ec8131475)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/2af9ee47-7a3c-43a6-84fb-b9f2111ed117)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
