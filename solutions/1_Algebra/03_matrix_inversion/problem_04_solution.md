### Exercise 4. Gauss-Jordan

## Question

Find $A^{-1}$ using the Gauss-Jordan method for:

$$
A=
\begin{pmatrix}
1 & 2 \\
3 & 5 \\
\end{pmatrix}
$$

Show the augmented matrix $[A\mid I]$ after successive operations and explain why obtaining $I$ on the left gives the inverse on the right.

## Solution

Start with the augmented matrix $[A \mid I]$:

$$
\begin{pmatrix}
1 & 2 & \mid & 1 & 0 \\
3 & 5 & \mid & 0 & 1 \\
\end{pmatrix}
$$

Perform $R_2 \leftarrow R_2 - 3R_1$:

$$
\begin{pmatrix}
1 & 2 & \mid & 1 & 0 \\
0 & -1 & \mid & -3 & 1 \\
\end{pmatrix}
$$

Perform $R_2 \leftarrow -R_2$:

$$
\begin{pmatrix}
1 & 2 & \mid & 1 & 0 \\
0 & 1 & \mid & 3 & -1 \\
\end{pmatrix}
$$

Perform $R_1 \leftarrow R_1 - 2R_2$:

$$
\begin{pmatrix}
1 & 0 & \mid & -5 & 2 \\
0 & 1 & \mid & 3 & -1 \\
\end{pmatrix}
$$

Therefore, the inverse is:

$$
A^{-1}=
\begin{pmatrix}
-5 & 2 \\
3 & -1 \\
\end{pmatrix}
$$

Each row operation is equivalent to multiplying the matrix on the left by an elementary matrix. Whatever sequence of steps turns $A$ into $I$ is the exact sequence that multiplies $A$ by $A^{-1}$. Applying those same steps to $I$ on the right computes $A^{-1}I = A^{-1}$.