### Exercise 2. Determinant of a 3x3 Matrix

## Question

For the matrix:

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 4 \\
2 & 1 & 5 \\
\end{pmatrix}
$$

Compute $\det A$ using Sarrus' rule. Then perform one simple check using a chosen property of the determinant.

## Solution

Using Sarrus' rule (multiplying along the diagonals):

$$
\begin{aligned}
\det A &= 1(3)(5) + 2(4)(2) + (-1)(0)(1) - (-1)(3)(2) - 1(4)(1) - 2(0)(5) \\
&= 15 + 16 + 0 - (-6) - 4 - 0 \\
&= 31 + 6 - 4 \\
&= 33
\end{aligned}
$$

To check this, we can compute the determinant by expanding along the first column, which has a zero to make things easier:

$$
\begin{aligned}
\det A &= 1(3(5) - 4(1)) - 0 + 2(2(4) - (-1)(3)) \\
&= 1(15 - 4) + 2(8 + 3) \\
&= 11 + 2(11) \\
&= 11 + 22 \\
&= 33
\end{aligned}
$$

The calculation is verified since both methods yield $33$. Sarrus' rule is a visual trick for $3 \times 3$ matrices, while expanding by a column works by breaking the matrix into smaller $2 \times 2$ pieces.