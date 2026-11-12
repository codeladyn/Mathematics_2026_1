### Exercise 10. Detecting Dependence

## Question

Without carrying out a full determinant calculation, explain why:

$$
\det
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & 6 \\
0 & 1 & 5 \\
\end{pmatrix}
=0
$$

Identify a specific dependence between the rows and connect it with noninvertibility of the matrix.

## Solution

If you look at the matrix, the second row is exactly two times the first row:

$$
\begin{pmatrix}
2 & 4 & 6 \\
\end{pmatrix}
= 2
\begin{pmatrix}
1 & 2 & 3 \\
\end{pmatrix}
$$

This means the rows are linearly dependent (one provides no new geometric information). Any matrix with a row that is a multiple of another will always have a determinant of exactly $0$. Because the determinant is zero, this matrix is fundamentally flat and therefore not invertible.