### Exercise 6. A System with a Parameter — Which Cases Actually Occur?

## Question

Analyze, depending on the parameter $a$, the system:

$$
\begin{cases}
x+y=2, \\
ax+ay=4.
\end{cases}
$$

Among the three possibilities — exactly one solution, infinitely many solutions, no solution — determine which actually occur and for which values of $a$. If one type cannot occur, explain why.

## Solution

Write the augmented matrix:

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
a & a & \mid & 4 \\
\end{pmatrix}
$$

Perform $R_2 \leftarrow R_2 - aR_1$:

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
0 & 0 & \mid & 4 - 2a \\
\end{pmatrix}
$$

- **Infinitely many solutions:** Occurs when $4 - 2a = 0$, which means $a = 2$. The second row becomes $0 = 0$, leaving $x + y = 2$ with one free variable.
- **No solution:** Occurs when $4 - 2a \neq 0$, which means $a \neq 2$. The second row becomes $0 = 4 - 2a \neq 0$, which is a contradiction.
- **Exactly one solution:** Cannot occur for any value of $a$. Because the second row of the coefficient matrix is always $a$ times the first row, elimination always produces two zeros on the left side of row 2, so there can never be a second pivot.