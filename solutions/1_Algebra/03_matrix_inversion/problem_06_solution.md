### Exercise 6. Solving a System Using the Inverse

## Question

Solve $Ax=b$, where:

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix}
$$

using $x=A^{-1}b$. Then substitute the resulting vector back into the equation and check the result.

## Solution

First, find $A^{-1}$. The determinant is $\det A = 2(3) - 1(1) = 5$.

$$
A^{-1} = \frac{1}{5}
\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix}
$$

Now compute $x = A^{-1}b$:

$$
\begin{aligned}
x &= \frac{1}{5}
\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix}
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix} \\
&= \frac{1}{5}
\begin{pmatrix}
15 - 7 \\
-5 + 14 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
\frac{8}{5} \\
\frac{9}{5} \\
\end{pmatrix}
\end{aligned}
$$

Check by substituting $x$ back into $Ax$:

$$
\begin{aligned}
Ax &=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix}
\begin{pmatrix}
\frac{8}{5} \\
\frac{9}{5} \\
\end{pmatrix} \\
&=
\begin{pmatrix}
\frac{16}{5} + \frac{9}{5} \\
\frac{8}{5} + \frac{27}{5} \\
\end{pmatrix} \\
&=
\begin{pmatrix}
\frac{25}{5} \\
\frac{35}{5} \\
\end{pmatrix} \\
&=
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix}
\end{aligned}
$$

This matches $b$, confirming that the solution is correct.