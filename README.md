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
# Register No:212224240121

# Developed By:A.Pugazh Sozhan

# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/17732007-e27d-473a-977e-9b995343adf0)


### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/340390ae-af46-490a-99ec-ff213ce6232d)


### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/7b960117-a7d3-4324-a7ff-4b5bda24c629)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
