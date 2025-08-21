# Experiment 8


AIM: MULTIDIMENSIONAL ARRAY
THEORY:

Take Matrix Input from User & Display It

A matrix is a 2D array arranged in rows and columns.

Use nested loops to input values into the matrix.

Display the matrix using nested loops without modifying data.

Addition of Two Matrices

Only possible if both matrices have the same dimensions.

Each element of the result is the sum of corresponding elements.

Uses nested loops to compute the sum matrix.

Commonly used in image processing and math computations.

Multiplication of Two Matrices

Possible if columns of first = rows of second matrix.

Each element in result is dot product of row and column.

Implemented with three nested loops.

Result dimensions: rows of first × columns of second.

Used in graphics, transformations, scientific computing.

Diagonal Addition of a Square Matrix

Works only for square matrices (rows = columns).

Sum main diagonal (top-left to bottom-right) and secondary diagonal (top-right to bottom-left).

If matrix size is odd, subtract center element once to avoid double counting.

Transpose of a Matrix

Interchange rows and columns to form transpose.

Dimensions change from m×n to n×m.

Implemented by swapping indices: new[j][i] = old[i][j].

Useful in symmetry checks and math operations.

Compare the Elements of the First Row to Second Row

Requires at least two rows.

Compare each element column-wise between first and second row.

Results indicate which row’s element is greater or if equal.

Useful for ranking, sorting, or analysis.

ALGORITHM:

Take Matrix Input from User and Display It

Start.

Input number of rows and columns.

Declare 2D array [rows][cols].

Loop through rows and columns to input elements.

Print the matrix elements with proper formatting.

End.

Addition of Matrices

Start.

Input rows and columns.

Declare matrix1, matrix2, and sum.

Input elements for both matrices.

Loop to add corresponding elements and store in sum.

Print the sum matrix.

End.

Multiplying Two Matrices

Start.

Input rows and columns of first (r1, c1) and second (r2, c2) matrices.

If c1 != r2, print error and stop.

Declare matrices A, B, and result initialized to 0.

Input elements for A and B.

Use three nested loops to calculate result[i][j] += A[i][k] * B[k][j].

Print resultant matrix.

End.

Diagonal Addition

Start.

Input size n of square matrix.

Declare matrix and initialize sums a = 0 (main), b = 0 (secondary).

Input elements and display matrix.

Loop through indices to sum diagonals.

Print diagonal sums and adjust if n is odd (subtract center once).

End.

Transpose of a Matrix

Start.

Input number of rows and columns.

Declare matrix and input elements.

Print transpose by interchanging rows and columns.

End.

Compare Two Rows Column-wise

Start.

Input number of rows and columns.

Compare each column element of first and second row.

Print which row’s element is greater or if equal for each column.

End.

CONCLUSION:

This experiment demonstrated multidimensional arrays in C++ by implementing matrix operations like input/output, addition, multiplication, diagonal summation, transpose, and row-wise comparison. It highlighted the use of nested loops and indexing for efficient handling of two-dimensional data structures.




