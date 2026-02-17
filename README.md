# Developed by: PAVITHRA E
# RegisterNumber:212224220072
# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: First import numpy module with nickname as np

Step 2: Then give the matrix row in np.array()

Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix and store it in the variable (i.e; rank)

Step 4: Now print the rank to get the output
## Program:
```
import numpy as np

A = np.array([[5, -3, -10],
              [2,  2,  -3],
              [-3, -1,  5]])


rank = np.linalg.matrix_rank(A)

print(rank)
```
## Output:
<img width="1916" height="952" alt="image" src="https://github.com/user-attachments/assets/bab64dd6-bbef-4598-8954-93e7c93847c5" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

