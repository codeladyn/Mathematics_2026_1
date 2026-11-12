### Exercise 6. Parameter and Invertibility

## Question

For the matrix depending on parameter $t$:

$$
A(t)=
\begin{pmatrix}
t & 1 \\
2 & t \\
\end{pmatrix}
$$

Find all values of $t$ for which the matrix is not invertible. Explain how your answer is related to the determinant being zero.

## Solution

First, compute the determinant of the matrix:

$$
\begin{aligned}
\det A(t) &= t(t) - 1(2) \\
&= t^2 - 2
\end{aligned}
$$

A matrix is not invertible when its determinant is equal to exactly zero. Therefore, we set the determinant to zero and solve for $t$:

$$
\begin{aligned}
t^2 - 2 &= 0 \\
t^2 &= 2
\end{aligned}
$$

This gives two possible values:

$$
t = \sqrt{2},\qquad t = -\sqrt{2}
$$

When $t$ is either $\sqrt{2}$ or $-\sqrt{2}$, the determinant drops to zero, which mathematically destroys the matrix's ability to be inverted (you cannot divide by zero in the inverse formula).