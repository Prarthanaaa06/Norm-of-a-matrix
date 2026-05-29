# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Algorithm for 1-Norm of a Matrix
Step 1: Start the program.

Step 2: Import the necessary library (numpy).

Step 3: Read the input matrix from the user (evaluated as a nested list).

Step 4: Compute the 1-norm using the built-in function np.linalg.norm(matrix, 1).

Step 5: Format the calculated norm to two decimal places.

Step 6: Display the result.

Step 7: Stop the program.
---
2. Algorithm for $L_2$-Norm of a Matrix
Step 1: Start the program.

Step 2: Import the necessary library (numpy).

Step 3: Read the input matrix from the user.

Step 4: Compute the infinity norm using the built-in function np.linalg.norm(matrix, np.inf).

Step 5: Format the calculated norm to two decimal places.

Step 6: Display the result.

Step 7: Stop the program.
---
3. Algorithm for Infinity Norm of a Matrix

Step 1: Start the program.

Step 2: Import the necessary library (numpy).

Step 3: Read the input matrix from the user.

Step 4: Compute the infinity norm using the built-in function np.linalg.norm(matrix, np.inf).

Step 5: Format the calculated norm to two decimal places.

Step 6: Display the result.

Step 7: Stop the program

## Program:
```Python
# Register No:212225230213
# Developed By: PRARTHANA D
# 1-Norm of a Matrix
import os 
os.environ['OPENBLAS_NUM_THREADS'] = '1'
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))

# 2-Norm of a Matrix

import os 
os.environ['OPENBLAS_NUM_THREADS'] = '1'
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))


# Infinity Norm of a Matrix

import os 
os.environ['OPENBLAS_NUM_THREADS'] = '1'
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))


```
## Output:
### 1-Norm of a Matrix

<img width="751" height="694" alt="image" src="https://github.com/user-attachments/assets/3b0cab68-d4bc-4246-ba65-d37d57ee3636" />

### 2-Norm of a Matrix

<img width="724" height="787" alt="image" src="https://github.com/user-attachments/assets/6f1bf806-13f4-4b3f-8913-e1f4e1a90abb" />


### Infinity Norm of a Matrix

<img width="870" height="789" alt="image" src="https://github.com/user-attachments/assets/88ae422a-f28e-4be0-a649-4e15589b60db" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
