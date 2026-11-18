### Exercise 4. Infinitely Many Solutions

## Question

Solve:

$$
\begin{cases}
x+y+z=2, \\
2x+2y+2z=4, \\
x-y+z=0.
\end{cases}
$$

Give the solution in parametric form, identify a free variable, and for one chosen parameter value check that the resulting point really satisfies the system.

## Solution

Write the augmented matrix:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 2 \\
2 & 2 & 2 & \mid & 4 \\
1 & -1 & 1 & \mid & 0 \\
\end{pmatrix}
$$

Perform $R_2 \leftarrow R_2 - 2R_1$ and $R_3 \leftarrow R_3 - R_1$:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 2 \\
0 & 0 & 0 & \mid & 0 \\
0 & -2 & 0 & \mid & -2 \\
\end{pmatrix}
$$

Swap $R_2$ and $R_3$, then divide $R_2$ by $-2$:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 2 \\
0 & 1 & 0 & \mid & 1 \\
0 & 0 & 0 & \mid & 0 \\
\end{pmatrix}
$$

From row 2, $y = 1$. There is no pivot in the $z$-column, so $z$ is a free variable. Let $z = t$, where $t \in \mathbb{R}$.
Substituting into row 1 gives $x + 1 + t = 2$, so $x = 1 - t$.

The parametric solution is:

$$
\begin{cases}
x = 1 - t, \\
y = 1, \\
z = t,
\end{cases}
$$

for any real number $t$.

Check for $t = 0$, which gives the point $(1, 1, 0)$:
- $1 + 1 + 0 = 2$ (true)
- $2(1) + 2(1) + 2(0) = 4$ (true)
- $1 - 1 + 0 = 0$ (true)

The point satisfies all three equations.