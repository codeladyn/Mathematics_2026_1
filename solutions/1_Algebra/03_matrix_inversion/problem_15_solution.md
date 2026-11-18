### Exercise 15. Two Methods for Solving the Same System

## Question

For:

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
7 \\
8 \\
\end{pmatrix}
$$

Solve $Ax=b$ in two ways:
1. using $A^{-1}b$,
2. using Gaussian elimination.

Compare both solutions, the number of essential steps, and state which method was simpler in this example.

## Solution

Method 1 (Using $A^{-1}b$):

The determinant is $\det A = 2(3) - 1(1) = 5$, so:

$$
A^{-1} = \frac{1}{5}
\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix}
$$

Multiply $A^{-1}b$:

$$
\begin{aligned}
x &= \frac{1}{5}
\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix}
\begin{pmatrix}
7 \\
8 \\
\end{pmatrix} \\
&= \frac{1}{5}
\begin{pmatrix}
21 - 8 \\
-7 + 16 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
\frac{13}{5} \\
\frac{9}{5} \\
\end{pmatrix}
\end{aligned}
$$

Method 2 (Gaussian elimination):

Set up the augmented matrix $[A \mid b]$:

$$
\begin{pmatrix}
2 & 1 & \mid & 7 \\
1 & 3 & \mid & 8 \\
\end{pmatrix}
$$

Swap $R_1$ and $R_2$ to get a $1$ in the top-left corner:

$$
\begin{pmatrix}
1 & 3 & \mid & 8 \\
2 & 1 & \mid & 7 \\
\end{pmatrix}
$$

Perform $R_2 \leftarrow R_2 - 2R_1$:

$$
\begin{pmatrix}
1 & 3 & \mid & 8 \\
0 & -5 & \mid & -9 \\
\end{pmatrix}
$$

From the second row, $-5x_2 = -9$, which gives $x_2 = \frac{9}{5}$. Substituting into the first row gives $x_1 + 3\left(\frac{9}{5}\right) = 8$, so $x_1 = \frac{40}{5} - \frac{27}{5} = \frac{13}{5}$. Thus:

$$
x=
\begin{pmatrix}
\frac{13}{5} \\
\frac{9}{5} \\
\end{pmatrix}
$$

Comparison: Both methods give the exact same answer. For a small $2\times2$ matrix, using $A^{-1}b$ was slightly faster and simpler because the $2\times2$ inverse formula is instant and avoids back-substitution. (For larger matrices, however, Gaussian elimination is usually much faster.)