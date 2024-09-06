# Vergara_PA2-Numerical-Python-NUMPY-
This respiratory contains Python codes for the given programming problems. Furthermore, solutions and explanations for each problem are written here.

# NORMALIZATION PROBLEM
The normalization problem involves the use of centering and scaling processes. These processes involve the data from the mean and its standard deviation. It can be expressed as 𝑍 = 𝑋 − 𝑥̅ / σ. Accordingly, this problem utilizes the functions '.mean()' and '.std()' to find the normalized random 5x5 ndarray. Moreover, the normalized result should be stored as a '.npy' file. 

Library: import numpy as np

Description: This allows access to NumPy features from the Library. Moreover, it allows the numpy to be shortened to np.

Function: np.random.random((5,5))

Description: This generates a random 5x5 ndarray, which is to be normalized.

Function: X.mean

Description: The variable X was assigned initially to the generated 5x5 random ndarray. Accordingly, this syntax gets the mean of the elements in X and is assigned to syntax X_mean.

Function: X.std

Description: This gets the standard deviation in X and is assigned to syntax X_std.

Function: (X - X_mean) / X_std

Description: The mathematical expression for normalization 𝑍 = 𝑋 − 𝑥̅ / σ is translated to Python codes by assigning variables or syntax to Python functions. Moreover, it gets the normalized X and is stored in syntax X_normalized.

Function: np.save('X_normalized.npy', X_normalized)

Description: It saves normalized ndarray as X_normalized.npy.

Function: print("X: \n", X, "\n") and print("X_normalized: \n", X_normalized)

Description: Print output for X and X_normalized in order to compare the original X and normalized X.

# Divisible by 3 Problem
The divisible by 3 problem aims to identify which of the following squares of the first 100 positive integers are divisible by three. This problem involves the use of 'np.arrange', 'np.reshape', '** 2', and '% == 0' to reach the expected output. Accordingly, it should save the result to a .npy file.

Library: import numpy as np

Description: This allows access to NumPy features from the Library. Moreover, it allows the numpy to be shortened to np.

Function: np.arange(1,101).reshape(10,10) ** 2

Description: This creates an ndarray of 1-100, arranges it to a 10x10 by the use of .reshape, and squares the first 100 positive integers through '** 2'. It is then stored to the variable A. Moreover, the codes can be observed as linear as they grant a cleaner line of code than if they are separated code by code.

Function: A[A % 3 == 0].reshape(3,11)

Description: This determines elements in A divisible by 3 by using modulo. Modulo works by setting the divisibility by 3, as observed in 'A % 3', and ensuring that the remainder is 0, as seen in '== 0'. Afterward, it is reshaped to a 3x11 array and stored to syntax 'div_by_3'.

Function: np.save('div_by_3.npy', div_by_3)

Description: It saves results from 'div_by_3' as 'div_by_3.npy'.

Funciton: print("A: \n", A, "\n") and print("div_by_3: \n", div_by_3)

Description: Prints outputs of A and div_by_3 to check which of the squared elements in A are divisible by 3.
