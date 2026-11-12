### Exercise 3. Swapping Two Rows

## Question

For the matrix:

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 3 & 1 \\
2 & 1 & 1 \\
\end{pmatrix}
$$

Compute $\det A$. Then form a matrix $B$ by swapping the first and second rows of $A$. 
First predict $\det B$ using a determinant property, and then verify your prediction by calculation.

## Solution

Expanding along the first row to compute $\det A$:

$$
\begin{aligned}
\det A &= 1(3(1) - 1(1)) - 2(0(1) - 1(2)) + 0 \\
&= 1(2) - 2(-2) \\
&= 2 + 4 \\
&= 6
\end{aligned}
$$

Matrix $B$ is formed by swapping the first and second rows of $A$:

$$
B=
\begin{pmatrix}
0 & 3 & 1 \\
1 & 2 & 0 \\
2 & 1 & 1 \\
\end{pmatrix}
$$

Prediction: A fundamental rule of determinants is that swapping any two rows flips the sign of the determinant. Therefore, $\det B$ should be $-6$.

Verification by expanding along the first column of $B$:

$$
\begin{aligned}
\det B &= 0 - 1(3(1) - 1(1)) + 2(3(0) - 1(2)) \\
&= -1(2) + 2(-2) \\
&= -2 - 4 \\
&= -6
\end{aligned}
$$

The calculation confirms the property: swapping two rows multiplies the determinant by $-1$.