# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Aim: To write a Python program to find the inverse of a matrix

### Step 1: Import the NumPy library to perform matrix operations.

### Step 2: Get the matrix elements from the user and convert them into a NumPy array.

### Step 3: Use the `numpy.linalg.inv()` function to calculate the inverse of the matrix.

### Step 4: Display the inverse of the given matrix as the output.

## Program:
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as p
a=p.array([[2,1,1],[1,1,1],[1,-1,2]])
b=p.linalg.inv(a)
print(b)
```
## Output:
<img width="1514" height="724" alt="image" src="https://github.com/user-attachments/assets/3b7a3c69-1ef5-46ec-b477-d6b7141af55a" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

