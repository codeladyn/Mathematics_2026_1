### Exercise 11. Parameter and Invertibility

## Question

For the matrix:

$$
A(t)=
\begin{pmatrix}
1 & t \\
t & 1 \\
\end{pmatrix}
$$

Find all $t$ for which the matrix is invertible, and then give a formula for $A(t)^{-1}$. Explain what happens to this formula at the excluded values.

## Solution

First, compute the determinant:

$$
\det A(t) = 1(1) - t(t) = 1 - t^2
$$

A matrix is invertible when its determinant is not zero:

$$
1 - t^2 \neq 0 \implies t \neq 1 \quad \mathrm{and} \quad t \neq -1
$$

For all $t \neq \pm 1$, the $2\times2$ inverse formula gives:

$$
A(t)^{-1} = \frac{1}{1-t^2}
\begin{pmatrix}
1 & -t \\
-t & 1 \\
\end{pmatrix}
$$

At the excluded values $t = 1$ and $t = -1$, the denominator $1 - t^2$ becomes $0$. Since you cannot divide by zero, the formula breaks down and the inverse does not exist.