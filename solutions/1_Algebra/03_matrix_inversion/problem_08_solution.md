### Exercise 8. Inverse of a Transformation

## Question

The matrix:

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & \frac{1}{2} \\
\end{pmatrix}
$$

describes a scaling of the plane. Find $S^{-1}$ and explain geometrically what the inverse transformation does. Check the action of the pair $S, S^{-1}$ on one simple vector.

## Solution

Since $S$ is a diagonal matrix, its inverse is found by taking the reciprocals of the diagonal entries:

$$
S^{-1}=
\begin{pmatrix}
\frac{1}{2} & 0 \\
0 & 2 \\
\end{pmatrix}
$$

Geometrically, $S$ stretches the x-coordinate by a factor of $2$ and shrinks the y-coordinate by half. The inverse $S^{-1}$ does the exact opposite: it shrinks the x-coordinate by half and stretches the y-coordinate by a factor of $2$, returning everything to its starting position.

Check using the simple vector $v$:

$$
v=
\begin{pmatrix}
1 \\
1 \\
\end{pmatrix}
$$

First apply $S$, then apply $S^{-1}$:

$$
Sv =
\begin{pmatrix}
2 & 0 \\
0 & \frac{1}{2} \\
\end{pmatrix}
\begin{pmatrix}
1 \\
1 \\
\end{pmatrix}
=
\begin{pmatrix}
2 \\
\frac{1}{2} \\
\end{pmatrix}
$$

$$
S^{-1}(Sv) =
\begin{pmatrix}
\frac{1}{2} & 0 \\
0 & 2 \\
\end{pmatrix}
\begin{pmatrix}
2 \\
\frac{1}{2} \\
\end{pmatrix}
=
\begin{pmatrix}
1 \\
1 \\
\end{pmatrix}
$$

The vector returns to its original value $v$.