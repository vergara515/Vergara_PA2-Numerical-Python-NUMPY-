# Vergara_PA2-Numerical-Python-NUMPY-
This respiratory contains Python codes for the given programming problems. Furthermore, solutions and explanations for each problem are written here.

# NORMALIZATION PROBLEM
Library: import numpy as np - importing from Library grants access to NumPy features)

Function: np.random.random((5,5)) - generates random 5x5 ndarray

Syntax: X.mean - gets the mean of elements in X

Syntax: X.std - gets the standard deviation in X

Function: (X - X_mean) / X_std - gets the normalized X

Function: np.save('X_normalized.npy', X_normalized) - saves normalized ndarray as X_normalized.npy

Function: print("X: \n", X, "\n") and print("X_normalized: \n", X_normalized) - prints output for X and X_normalized

# Divisible by 3 Problem
Library: import numpy as np - importing from Library grants access to NumPy features)

Function: np.arange(1,101).reshape(10,10) ** 2 - creates ndarray of 1-100, arranges it to a 10x10, and squares the first 100 positive integers

Function: A[A % 3 == 0].reshape(3,11) - determines elements divisible by 3 and arranges it to a 3x11

Function: np.save('div_by_3.npy', div_by_3) - saves results from div_by_3 as div_by_3.npy

Funciton: print("A: \n", A, "\n") and print("div_by_3: \n", div_by_3) - prints output of A and div_by_3
