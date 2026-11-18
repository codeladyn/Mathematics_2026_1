### Exercise 2. Gaussian Elimination — One Solution

## Question

Solve using Gaussian elimination:

$$\begin{cases} x+y+z=6, \\ 2x-y+z=3, \\ x+2y-z=2. \end{cases}$$

After solving, substitute the result into all equations and check consistency.

## Solution

Write the augmented matrix:

$$\begin{pmatrix} 1 & 1 & 1 & \mid & 6 \\ 2 & -1 & 1 & \mid & 3 \\ 1 & 2 & -1 & \mid & 2 \\ \end{pmatrix}$$

Eliminate $x$ from rows 2 and 3 using $R_2 \leftarrow R_2 - 2R_1$ and $R_3 \leftarrow R_3 - R_1$:

$$\begin{pmatrix} 1 & 1 & 1 & \mid & 6 \\ 0 & -3 & -1 & \mid & -9 \\ 0 & 1 & -2 & \mid & -4 \\ \end{pmatrix}$$

Swap $R_2$ and $R_3$ to put $1$ in the pivot position:

$$\begin{pmatrix} 1 & 1 & 1 & \mid & 6 \\ 0 & 1 & -2 & \mid & -4 \\ 0 & -3 & -1 & \mid & -9 \\ \end{pmatrix}$$

Eliminate $y$ from row 3 using $R_3 \leftarrow R_3 + 3R_2$:

$$\begin{pmatrix} 1 & 1 & 1 & \mid & 6 \\ 0 & 1 & -2 & \mid & -4 \\ 0 & 0 & -7 & \mid & -21 \\ \end{pmatrix}$$

Now use back-substitution:
- From row 3: $-7z = -21 \implies z = 3$.
- From row 2: $y - 2(3) = -4 \implies y = 2$.
- From row 1: $x + 2 + 3 = 6 \implies x = 1$.

The unique solution is $(x, y, z) = (1, 2, 3)$.

Verification by substituting into all three original equations:
- $1 + 2 + 3 = 6$ (true)
- $2(1) - 2 + 3 = 3$ (true)
- $1 + 2(2) - 3 = 2$ (true)

All three equations hold, so the solution is consistent.