### Exercise 7. Using Properties Instead of Recomputing

## Question

Suppose that for a $3\times3$ matrix, $\det A=-4$. Compute:

$$
\det(2A),\qquad \det(A^T),\qquad \det(A^2),\qquad \det(-A)
$$

Justify each answer using the appropriate property.

## Solution

Computation for $\det(2A)$:

$$
\begin{aligned}
\det(2A) &= 2^3 \det A \\
&= 8(-4) \\
&= -32
\end{aligned}
$$

When a $3 \times 3$ matrix is multiplied by a scalar, the scalar multiplies each of the 3 rows, so it factors out as $2^3$.

Computation for $\det(A^T)$:

$$
\det(A^T) = \det A = -4
$$

Transposing a matrix (swapping rows and columns) never changes its determinant.

Computation for $\det(A^2)$:

$$
\begin{aligned}
\det(A^2) &= (\det A)^2 \\
&= (-4)^2 \\
&= 16
\end{aligned}
$$

The determinant of a product is the product of the determinants.

Computation for $\det(-A)$:

$$
\begin{aligned}
\det(-A) &= (-1)^3 \det A \\
&= -1(-4) \\
&= 4
\end{aligned}
$$

Similar to the first part, multiplying the matrix by $-1$ applies to all 3 rows, factoring out as $(-1)^3 = -1$.