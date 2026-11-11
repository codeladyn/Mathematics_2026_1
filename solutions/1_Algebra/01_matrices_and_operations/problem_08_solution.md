### Exercise 8. Row Operations and Their Reversibility

**Result**

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

**Explanation**

You can change rows around (like adding them together or swapping them) to solve systems. This shows that every move you make has an exact opposite move that can undo it, so you never permanently break the matrix.