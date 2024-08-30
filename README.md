# Aim:
To study and implement 2 Dimensional arrays in C++

## Theory:

A 2D array is a data structure that with a grid, where each element is identified by two indices: a row index and a column index.

Features of 2D array:

Structure: A 2D array is essentially an array of arrays, where each element of the outer array is another array representing a row in the matrix.
Indexing: Elements in a 2D array are accessed using two indices.
Contiguous Memory: In C++, a 2D array is stored in memory as a continuous block of memory.
Operations: Various operations can be performed on 2D arrays, including addition, subtraction, and multiplication (in the case of matrices).

Uses of 2D Arrays:

Used in applications including computer graphics, image processing.
Used in scientific simulations, spreadsheets.
Used in mathematical representation of matrix.

## Algorithm:

### Multiplication of Matrices.

1.Input Matrix Dimensions:

Matrix A: Number of rows (rA) and columns (cA).
Matrix B: Number of rows (rB) and columns (cB).

2.Check Matrix Multiplication Validity:

Ensure that the number of columns in Matrix A (cA) matches the number of rows in Matrix B (rB). If not, matrix multiplication cannot be performed.

3.Allocate Memory for Matrices:

Create Matrix A of size rA x cA.
Create Matrix B of size rB x cB.
Create Matrix C for the result of size rA x cB and initialize it to zero.

4.Input Matrix Elements:

Input elements for Matrix A.
Input elements for Matrix B.

5.Perform Matrix Multiplication:

Initialize all elements of Matrix C to 0.

For each element C[i][j] in the resulting matrix:

Compute C[i][j] as the sum of the products of corresponding elements from the row i of Matrix A and column j of Matrix B.

6.Output the Result:

7.Display the resultant Matrix C.

8.Stop
