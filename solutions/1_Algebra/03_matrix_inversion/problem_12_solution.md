### Exercise 12. Finding Inverses Without Starting from Scratch

## Question

It is known that:

$$
A^{-1}=
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}
$$

Without finding $A$, compute $(3A)^{-1}$, $(A^T)^{-1}$, and $(A^2)^{-1}$. Justify each result using the appropriate property.

## Solution

1. For $(3A)^{-1}$, use the scalar property $(cA)^{-1} = \frac{1}{c}A^{-1}$:

$$
(3A)^{-1} = \frac{1}{3}A^{-1} =
\begin{pmatrix}
\frac{2}{3} & -\frac{1}{3} \\
-1 & \frac{2}{3} \\
\end{pmatrix}
$$

2. For $(A^T)^{-1}$, use the transpose property $(A^T)^{-1} = (A^{-1})^T$:

$$
(A^T)^{-1} = (A^{-1})^T =
\begin{pmatrix}
2 & -3 \\
-1 & 2 \\
\end{pmatrix}
$$

3. For $(A^2)^{-1}$, use the power property $(A^2)^{-1} = (A^{-1})^2$:

$$
\begin{aligned}
(A^2)^{-1} &= A^{-1}A^{-1} \\
&=
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
4 + 3 & -2 - 2 \\
-6 - 6 & 3 + 4 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
7 & -4 \\
-12 & 7 \\
\end{pmatrix}
\end{aligned}
$$

Using these inverse properties lets us find the answers directly from $A^{-1}$ without ever having to calculate the original matrix $A$.