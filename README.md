# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1:
Get the input matrix using np.array()  
## Step2: 
Find the 2-norm of the matrix using np.linalg.norm()
## Step3:
Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: PRADEP.E
# Developed By: 212223230149
# 1-Norm of a Matrix
import numpy as np 
value= eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix
import numpy as np 
value= eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix
import numpy as np 
value= eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix
![1](https://github.com/pradeeprajeswari/Norm-of-a-matrix/assets/145743112/5bea5e30-f65a-41be-a94f-82ee0adadc2c)

### 2-Norm of a Matrix
![2](https://github.com/pradeeprajeswari/Norm-of-a-matrix/assets/145743112/317c9b4d-16c1-491e-90ec-d0a90ef99b0c)

### Infinity Norm of a Matrix
![3](https://github.com/pradeeprajeswari/Norm-of-a-matrix/assets/145743112/04b87277-d572-4ec6-a856-70576d7aa12a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
