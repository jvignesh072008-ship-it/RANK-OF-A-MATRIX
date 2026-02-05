# RANK-OF-A-MATRIX

## Aim:

To write a python program to find the rank of a matrix

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1: Import Library: Import the NumPy library (import numpy as np) to access linear algebra functions.
### Step 2:Define Matrix: Define the input matrix as a nested list or NumPy array structure, e.g., arr = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]]).
### Step 3:Compute SVD: Use np.linalg.matrix_rank to perform Singular Value Decomposition (SVD) on the matrix, which finds its singular values.
### Step 4:Thresholding & Rank Count: Count the number of singular values that are greater than a small threshold (default tolerance), which represents the linearly independent rows/columns. 
### Step 5:Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: VIGNESH J
#RegisterNumber: 212225230297
#RefNumber: 25014705

import numpy as np
arr = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
result = np.linalg.matrix_rank(arr)
print(result)

```
## Output:

<img width="1189" height="779" alt="Screenshot 2026-02-03 112624" src="https://github.com/user-attachments/assets/e7fad63a-6e60-4d23-81b4-e751f6fdd0ca" />


## Result:

Thus the rank for the given matrix is successfully solved by  using a python program.

