# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step 1: 
import numpy as np
### Step 2: 
take the inputs as A = np.array([[1,2,3],[3,6,9]])
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
print (rank)
### step 5:
end the program

## Program:
```python
#Program to find the rank of a matrix.
#Developed by: POOJA A
#RegisterNumber:22007907
import numpy as np
A = np.array([[1,2,3],[3,6,9]])
rank = np.linalg.matrix_rank(A)
print(rank)
```

## Output:
![](./rank.png)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

