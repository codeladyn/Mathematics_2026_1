### Exercise 5. A 3x3 Matrix

## Question

Use Gauss-Jordan elimination to find the inverse of:

$$
A=
\begin{pmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
\end{pmatrix}
$$

Check the result by multiplication.

## Solution

Set up the augmented matrix $[A \mid I]$:

$$
\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 1 & \mid & 0 & 1 & 0 \\
1 & 0 & 1 & \mid & 0 & 0 & 1 \\
\end{pmatrix}
$$

Perform $R_3 \leftarrow R_3 - R_1$:

$$
\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 1 & \mid & 0 & 1 & 0 \\
0 & -1 & 1 & \mid & -1 & 0 & 1 \\
\end{pmatrix}
$$

Perform $R_3 \leftarrow R_3 + R_2$:

$$
\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 1 & \mid & 0 & 1 & 0 \\
0 & 0 & 2 & \mid & -1 & 1 & 1 \\
\end{pmatrix}
$$

Perform $R_3 \leftarrow \frac{1}{2}R_3$:

$$
\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 1 & \mid & 0 & 1 & 0 \\
0 & 0 & 1 & \mid & -\frac{1}{2} & \frac{1}{2} & \frac{1}{2} \\
\end{pmatrix}
$$

Perform $R_2 \leftarrow R_2 - R_3$:

$$
\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 0 & \mid & \frac{1}{2} & \frac{1}{2} & -\frac{1}{2} \\
0 & 0 & 1 & \mid & -\frac{1}{2} & \frac{1}{2} & \frac{1}{2} \\
\end{pmatrix}
$$

Perform $R_1 \leftarrow R_1 - R_2$:

$$
\begin{pmatrix}
1 & 0 & 0 & \mid & \frac{1}{2} & -\frac{1}{2} & \frac{1}{2} \\
0 & 1 & 0 & \mid & \frac{1}{2} & \frac{1}{2} & -\frac{1}{2} \\
0 & 0 & 1 & \mid & -\frac{1}{2} & \frac{1}{2} & \frac{1}{2} \\
\end{pmatrix}
$$

Thus, the inverse matrix is:

$$
A^{-1}=
\begin{pmatrix}
\frac{1}{2} & -\frac{1}{2} & \frac{1}{2} \\
\frac{1}{2} & \frac{1}{2} & -\frac{1}{2} \\
-\frac{1}{2} & \frac{1}{2} & \frac{1}{2} \\
\end{pmatrix}
$$

Check by multiplying $AA^{-1}$:

$$
\begin{aligned}
AA^{-1} &=
\begin{pmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
\frac{1}{2} & -\frac{1}{2} & \frac{1}{2} \\
\frac{1}{2} & \frac{1}{2} & -\frac{1}{2} \\
-\frac{1}{2} & \frac{1}{2} & \frac{1}{2} \\
\end{pmatrix} \\
&=
\begin{pmatrix}
\frac{1}{2}+\frac{1}{2}+0 & -\frac{1}{2}+\frac{1}{2}+0 & \frac{1}{2}-\frac{1}{2}+0 \\
0+\frac{1}{2}-\frac{1}{2} & 0+\frac{1}{2}+\frac{1}{2} & 0-\frac{1}{2}+\frac{1}{2} \\
\frac{1}{2}+0-\frac{1}{2} & -\frac{1}{2}+0+\frac{1}{2} & \frac{1}{2}+0+\frac{1}{2} \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

Since $AA^{-1} = I$, the solution is correct.