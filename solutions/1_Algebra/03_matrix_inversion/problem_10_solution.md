### Exercise 10. Inverse of a Diagonal Matrix

## Question

Given the matrices:

$$
D=
\begin{pmatrix}
2 & 0 & 0 \\
0 & -3 & 0 \\
0 & 0 & 5 \\
\end{pmatrix},\qquad E=
\begin{pmatrix}
2 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}
$$

Without using Gauss-Jordan elimination, decide which matrix is invertible. For the invertible matrix, give the inverse and check the result by multiplication.

## Solution

Matrix $D$ is invertible because all of its diagonal entries are nonzero ($\det D = 2(-3)(5) = -30 \neq 0$). Matrix $E$ is not invertible because it has a $0$ on its main diagonal (making an entire row of zeros and $\det E = 0$).

The inverse of a diagonal matrix is formed by taking the reciprocal of each diagonal entry:

$$
D^{-1}=
\begin{pmatrix}
\frac{1}{2} & 0 & 0 \\
0 & -\frac{1}{3} & 0 \\
0 & 0 & \frac{1}{5} \\
\end{pmatrix}
$$

Check by multiplication:

$$
\begin{aligned}
DD^{-1} &=
\begin{pmatrix}
2 & 0 & 0 \\
0 & -3 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}
\begin{pmatrix}
\frac{1}{2} & 0 & 0 \\
0 & -\frac{1}{3} & 0 \\
0 & 0 & \frac{1}{5} \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

Since $DD^{-1} = I$, the inverse is verified.