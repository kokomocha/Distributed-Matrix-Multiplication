# Synthetic Data Generation
This folder contains python classes to create synthetic data for matrix multiplication and matrix inverse. Only numpy is required to run the files. The following provides a short summary on the required class inputs of each program. 

Output files can be generated by calling the method "save_to_csv", the only input to this method is the output file name. The values for these matrices are randomly generated by numpy.

matrixMultiplicationSyntheticData.py
---------------------------------------
<ins>Inputs</ins>

row: Number of rows in matrix

col: Number of columns in matrix

min_value: Minimum value inside matrix

max_value: Maximum value inside matrix

seed: Seed number for random number generator


psdMatrixSyntheticData.py
---------------------------------------
<ins>Inputs</ins>

n: One side dimension of square matrix

min_value: Minimum value inside matrix

max_value: Maximum value inside matrix

seed: Seed number for random number generator
