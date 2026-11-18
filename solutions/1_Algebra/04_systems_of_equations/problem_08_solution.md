### Exercise 8. Two Systems with the Same Coefficient Matrix

## Question

Solve by elimination the two systems:

**System 1**

$$
\begin{cases}
2x+y=5, \\
x-y=1,
\end{cases}
$$

**System 2**

$$
\begin{cases}
2x+y=1, \\
x-y=4.
\end{cases}
$$

Compare the successive elimination steps. Which part of the calculation is the same in both cases, and why?

## Solution

**System 1:**

$$
\begin{pmatrix}
2 & 1 & \mid & 5 \\
1 & -1 & \mid & 1 \\
\end{pmatrix}
$$

Swap $R_1$ and $R_2$:

$$
\begin{pmatrix}
1 & -1 & \mid & 1 \\
2 & 1 & \mid & 5 \\
\end{pmatrix}
$$

Perform $R_2 \leftarrow R_2 - 2R_1$:

$$
\begin{pmatrix}
1 & -1 & \mid & 1 \\
0 & 3 & \mid & 3 \\
\end{pmatrix}
$$

From row 2, $3y = 3 \implies y = 1$. From row 1, $x - 1 = 1 \implies x = 2$.

**System 2:**

$$
\begin{pmatrix}
2 & 1 & \mid & 1 \\
1 & -1 & \mid & 4 \\
\end{pmatrix}
$$

Swap $R_1$ and $R_2$:

$$
\begin{pmatrix}
1 & -1 & \mid & 4 \\
2 & 1 & \mid & 1 \\
\end{pmatrix}
$$

Perform $R_2 \leftarrow R_2 - 2R_1$:

$$
\begin{pmatrix}
1 & -1 & \mid & 4 \\
0 & 3 & \mid & -7 \\
\end{pmatrix}
$$

From row 2, $3y = -7 \implies y = -\frac{7}{3}$. From row 1, $x - \left(-\frac{7}{3}\right) = 4 \implies x = \frac{5}{3}$.

**Comparison:** The exact same row operations (swapping rows, then $R_2 \leftarrow R_2 - 2R_1$) and the entire left side of the augmented matrix are identical in both cases. This happens because elimination steps are chosen solely to simplify the coefficient matrix, independent of the right-hand side.