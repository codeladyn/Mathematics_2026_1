### Exercise 9. Area and the Determinant

## Question

The vectors:

$$
u=
\begin{pmatrix}
3 \\
1 \\
\end{pmatrix},\qquad v=
\begin{pmatrix}
1 \\
4 \\
\end{pmatrix}
$$

span a parallelogram. Compute its area using a determinant. Then reverse the order of the vectors and explain what changes in the determinant and what does not change in the area.

## Solution

We place the vectors as columns in a matrix and compute the determinant:

$$
\begin{aligned}
\det
\begin{pmatrix}
3 & 1 \\
1 & 4 \\
\end{pmatrix}
&= 3(4) - 1(1) \\
&= 12 - 1 \\
&= 11
\end{aligned}
$$

The area of the parallelogram is the absolute value of the determinant, which is $11$.

If we reverse the order of the vectors, the matrix becomes:

$$
\begin{aligned}
\det
\begin{pmatrix}
1 & 3 \\
4 & 1 \\
\end{pmatrix}
&= 1(1) - 3(4) \\
&= 1 - 12 \\
&= -11
\end{aligned}
$$

The determinant changes sign to negative because swapping columns reverses the mathematical orientation. However, the physical area remains exactly $11$, because area is always measured as the absolute value of the determinant.