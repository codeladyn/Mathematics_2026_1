### Exercise 2. Formula for a 2x2 Matrix

## Question

Find the inverse of:

$$
A=
\begin{pmatrix}
3 & 2 \\
5 & 4 \\
\end{pmatrix}
$$

using the formula for a $2\times2$ matrix. At the end, check the result by computing one product with $A$.

## Solution

First, compute the determinant of $A$:

$$
\det A = 3(4) - 2(5) = 12 - 10 = 2
$$

Since $\det A \neq 0$, the inverse exists. Using the $2\times2$ inverse formula (swap the main diagonal, flip the signs of the other diagonal, and divide by the determinant):

$$
\begin{aligned}
A^{-1} &= \frac{1}{2}
\begin{pmatrix}
4 & -2 \\
-5 & 3 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2 & -1 \\
-\frac{5}{2} & \frac{3}{2} \\
\end{pmatrix}
\end{aligned}
$$

Check by computing $AA^{-1}$:

$$
\begin{aligned}
AA^{-1} &=
\begin{pmatrix}
3 & 2 \\
5 & 4 \\
\end{pmatrix}
\begin{pmatrix}
2 & -1 \\
-\frac{5}{2} & \frac{3}{2} \\
\end{pmatrix} \\
&=
\begin{pmatrix}
6 - 5 & -3 + 3 \\
10 - 10 & -5 + 6 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

Because $AA^{-1} = I$, the inverse is verified.