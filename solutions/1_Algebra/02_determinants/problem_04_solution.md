### Exercise 4. Triangular Matrix

## Question

Without expanding the determinant, compute:

$$
\det
\begin{pmatrix}
2 & 4 & 1 \\
0 & -3 & 5 \\
0 & 0 & 7 \\
\end{pmatrix}
$$

State the rule for an arbitrary triangular matrix and explain it using this example.

## Solution

$$
\begin{aligned}
\det
\begin{pmatrix}
2 & 4 & 1 \\
0 & -3 & 5 \\
0 & 0 & 7 \\
\end{pmatrix}
&= 2(-3)(7) \\
&= -42
\end{aligned}
$$

The rule states that for any triangular matrix (where all numbers below or above the main diagonal are zero), the determinant is simply the product of the numbers on the main diagonal. This happens because if you expand the determinant along the bottom row, the zeros cancel out the other calculations, leaving only the diagonal numbers to be multiplied together.