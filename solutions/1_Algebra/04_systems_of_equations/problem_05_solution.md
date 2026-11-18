### Exercise 5. Row Echelon Form and Number of Solutions

## Question

For the augmented matrix:

$$
\begin{pmatrix}
1 & 2 & -1 & \mid & 3 \\
0 & 1 & 2 & \mid & 1 \\
0 & 0 & 0 & \mid & 0 \\
\end{pmatrix}
$$

Determine the number of solutions and write them in parametric form. Explain how you know how many variables may be chosen freely.

## Solution

The bottom row is $0 = 0$, so there is no contradiction and the system is consistent. There are $3$ variables ($x, y, z$) and only $2$ pivot columns (for $x$ and $y$). Because the number of free variables equals the total number of variables minus the number of pivots ($3 - 2 = 1$), there is $1$ free variable ($z$) and therefore infinitely many solutions.

Let $z = t$, where $t \in \mathbb{R}$.
- From row 2: $y + 2t = 1 \implies y = 1 - 2t$.
- From row 1: $x + 2(1 - 2t) - t = 3 \implies x + 2 - 5t = 3 \implies x = 1 + 5t$.

The parametric solution is:

$$
\begin{cases}
x = 1 + 5t, \\
y = 1 - 2t, \\
z = t.
\end{cases}
$$