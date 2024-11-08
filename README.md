# EX-7 Norm of a matrix
# Date:
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
Register No:212222100038
Developed By:V.Prithviraj
1-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



3.Infinity Norm of a Matrix
import numpy as np
mat= np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-11-08 200320](https://github.com/user-attachments/assets/c984aae6-1f05-4075-bf16-3056dd854be2)



### 2-Norm of a Matrix

![Screenshot 2024-11-08 200432](https://github.com/user-attachments/assets/106d520e-97d3-4791-bb6c-8c2a9003cb9e)


### Infinity Norm of a Matrix

![Screenshot 2024-11-08 200517](https://github.com/user-attachments/assets/3225d45d-355f-4661-9ec5-e8882db4598c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
