### Exercise 14. A Matrix That Is Its Own Inverse

## Question

Assume that a square matrix $A$ satisfies:

$$
A^2=I
$$

Show that $A^{-1}=A$. Then give an example of a $2\times2$ matrix different from $I$ and $-I$ that satisfies this condition, and verify it by multiplication.

## Solution

By definition, a matrix $B$ is the inverse of $A$ if $AB = I$ and $BA = I$. Since we are given that $A^2 = I$, we can write this as:

$$
A \cdot A = I
$$

This directly satisfies the definition of an inverse with $B = A$, which proves that $A^{-1} = A$.

An example of a $2\times2$ matrix (other than $I$ and $-I$) that is its own inverse is the matrix that swaps coordinates:

$$
A=
\begin{pmatrix}
0 & 1 \\
1 & 0 \\
\end{pmatrix}
$$

Verification by multiplication:

$$
\begin{aligned}
A^2 &=
\begin{pmatrix}
0 & 1 \\
1 & 0 \\
\end{pmatrix}
\begin{pmatrix}
0 & 1 \\
1 & 0 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
0+1 & 0+0 \\
0+0 & 1+0 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

Because $A^2 = I$, this matrix is its own inverse.