# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
 1. Get the input matrix using np.array()   
 2. Find the 2-norm of the matrix using np.linalg.norm()
 3. Print the norm of the matrix in two decimal places

    
## Program:
# 1-Norm of a Matrix

                                 #Developed by: SADHANA SHREE B
                                 #Register Number: 212223230177

                                 import numpy as np
                                 mat = np.array(eval(input()))
                                 ans = np.linalg.norm(mat,1)
                                 Norm_of_matrix = "{:.2f}".format(ans)
                                 print(Norm_of_matrix)


# 2-Norm of a Matrix

                                 #Developed by: SADHANA SHREE B
                                 #Register Number: 212223230177

                                 import numpy as np
                                 mat = np.array(eval(input()))
                                 ans = np.linalg.norm(mat,2)
                                 Norm_of_matrix = "{:.2f}".format(ans)
                                 print(Norm_of_matrix)



# Infinity Norm of a Matrix

                                 #Developed by: SADHANA SHREE B
                                 #Register Number: 212223230177

                                 import numpy as np
                                 mat = np.array(eval(input()))
                                 ans = np.linalg.norm(mat,np.inf)
                                 Norm_of_matrix = "{:.2f}".format(ans)
                                 print(Norm_of_matrix)





## Output:
### 1-Norm of a Matrix

![Screenshot 2024-04-27 040245](https://github.com/SadhanaShreee/Norm-of-a-matrix/assets/144517664/e43c3f05-d37c-4fc9-ba8d-580b4e93e7d2)


### 2-Norm of a Matrix

![Screenshot 2024-04-27 040157](https://github.com/SadhanaShreee/Norm-of-a-matrix/assets/144517664/2abbc74c-ea0a-4ac4-8489-7444c1e3b9ec)


### Infinity Norm of a Matrix

![Screenshot 2024-04-27 040211](https://github.com/SadhanaShreee/Norm-of-a-matrix/assets/144517664/9a35b72b-ec91-4665-87e7-2275d9f20f0e)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
