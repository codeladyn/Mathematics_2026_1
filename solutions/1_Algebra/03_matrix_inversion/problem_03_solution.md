### Exercise 3. When Does the Inverse Not Exist?

## Question

For the matrix:

$$
A=
\begin{pmatrix}
2 & 4 \\
1 & 2 \\
\end{pmatrix}
$$

Explain in two ways why $A^{-1}$ does not exist: using the determinant and using dependence between the rows.

## Solution

Method 1 (Determinant):

$$
\det A = 2(2) - 4(1) = 4 - 4 = 0
$$

Because the determinant is $0$, the inverse formula would require dividing by zero, which is impossible. Therefore, $A^{-1}$ does not exist.

Method 2 (Row dependence):

Looking at the rows of $A$, the first row is simply twice the second row:

$$
\begin{pmatrix}
2 & 4 \\
\end{pmatrix}
= 2
\begin{pmatrix}
1 & 2 \\
\end{pmatrix}
$$

Because one row is a direct multiple of the other, the rows are linearly dependent. A matrix with dependent rows collapses information and cannot be reversed, meaning it has no inverse.