### Exercise 5. Row Operations

## Question

For the matrix:

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 1 & 0 \\
-1 & 4 & 2 \\
\end{pmatrix}
$$

Find $\det A$ by simplifying the matrix with row operations. At each step, indicate whether and how the determinant changes.

## Solution

We start with the original matrix and eliminate the numbers below the top-left $1$. 

Step 1: Replace row 2 with row 2 minus 2 times row 1 ($R_2 \leftarrow R_2 - 2R_1$). Adding a multiple of one row to another does not change the determinant.

$$
\det A = \det
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
-1 & 4 & 2 \\
\end{pmatrix}
$$

Step 2: Replace row 3 with row 3 plus row 1 ($R_3 \leftarrow R_3 + R_1$). This operation also does not change the determinant.

$$
\det A = \det
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 6 & 5 \\
\end{pmatrix}
$$

Step 3: Replace row 3 with row 3 plus 2 times row 2 ($R_3 \leftarrow R_3 + 2R_2$). Again, the determinant remains unchanged.

$$
\det A = \det
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 0 & -7 \\
\end{pmatrix}
$$

The matrix is now upper triangular. The determinant is the product of its main diagonal:

$$
\det A = 1(-3)(-7) = 21
$$

Because none of the row operations we used change the value of the determinant, the determinant of the original matrix $A$ is $21$.