### Exercise 3. Inconsistent System

## Question

Solve or show that the system is inconsistent:

$$
\begin{cases}
x+2y=3, \\
2x+4y=7.
\end{cases}
$$

Show how the contradiction appears in the matrix after elimination and interpret it in terms of equations.

## Solution

Write the augmented matrix:

$$
\begin{pmatrix}
1 & 2 & \mid & 3 \\
2 & 4 & \mid & 7 \\
\end{pmatrix}
$$

Perform $R_2 \leftarrow R_2 - 2R_1$:

$$
\begin{pmatrix}
1 & 2 & \mid & 3 \\
0 & 0 & \mid & 1 \\
\end{pmatrix}
$$

The second row translates to the equation $0x + 0y = 1$, or simply $0 = 1$, which is impossible. Because elimination leads to a false statement, the system is inconsistent and has no solution.