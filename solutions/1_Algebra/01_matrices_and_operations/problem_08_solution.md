### Exercise 8. Row Operations and Their Reversibility

## Question

For the matrix:

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\
2 & 4 & 1 \\
-1 & 1 & 3 \\
\end{pmatrix}
$$

Perform, in order:
1. $R_2\leftarrow R_2-2R_1$,
2. $R_3\leftarrow R_3+R_1$,
3. interchange $R_2$ and $R_3$.

Write the matrix after each step. Then, for each of the three operations, state an operation that reverses it.

## Solution

Step 1: $R_2 \leftarrow R_2 - 2R_1$

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 3 \\
-1 & 1 & 3 \\
\end{pmatrix}
$$

The reverse operation is $R_2 \leftarrow R_2 + 2R_1$.

Step 2: $R_3 \leftarrow R_3 + R_1$

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 3 \\
0 & 3 & 2 \\
\end{pmatrix}
$$

The reverse operation is $R_3 \leftarrow R_3 - R_1$.

Step 3: Interchange $R_2$ and $R_3$

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 2 \\
0 & 0 & 3 \\
\end{pmatrix}
$$

The reverse operation is to interchange $R_2$ and $R_3$ again.

You can change rows around to solve systems. This shows that every move you make has an exact opposite move that can undo it, meaning row operations do not permanently destroy or break the underlying data.