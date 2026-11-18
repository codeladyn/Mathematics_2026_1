### Exercise 9. A System from a Sum Condition

## Question

Find numbers $x, y$ satisfying:

$$
x+y=10,\qquad 2x+5y=32.
$$

Solve the system and explain geometrically why the solution is unique.

## Solution

Write the augmented matrix:

$$
\begin{pmatrix}
1 & 1 & \mid & 10 \\
2 & 5 & \mid & 32 \\
\end{pmatrix}
$$

Perform $R_2 \leftarrow R_2 - 2R_1$:

$$
\begin{pmatrix}
1 & 1 & \mid & 10 \\
0 & 3 & \mid & 12 \\
\end{pmatrix}
$$

From row 2, $3y = 12 \implies y = 4$.
From row 1, $x + 4 = 10 \implies x = 6$.

Check: $6 + 4 = 10$ and $2(6) + 5(4) = 12 + 20 = 32$.

Geometrically, each equation represents a straight line in the plane: $y = -x + 10$ (slope $-1$) and $y = -\frac{2}{5}x + \frac{32}{5}$ (slope $-\frac{2}{5}$). Because the two lines have different slopes, they are not parallel and must cross at exactly one intersection point, $(6, 4)$.