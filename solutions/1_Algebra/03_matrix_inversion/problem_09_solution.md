### Exercise 9. Matrix Equation

## Question

Given the matrices:

$$
A=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix}
$$

Solve the equation $AX=B$ for $X$. Before calculating, decide on which side of the equation $A^{-1}$ must be used. Then check the result by computing $AX$.

## Solution

Because $A$ is on the left side of $X$, we must multiply both sides of the equation on the left by $A^{-1}$ so that $A^{-1}A = I$ cancels $A$ out:

$$
X = A^{-1}B
$$

Since $\det A = 1(1) - 2(0) = 1$, the inverse of $A$ is:

$$
A^{-1}=
\begin{pmatrix}
1 & -2 \\
0 & 1 \\
\end{pmatrix}
$$

Now compute $X$:

$$
\begin{aligned}
X &=
\begin{pmatrix}
1 & -2 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
3 - 4 & 1 - 8 \\
0 + 2 & 0 + 4 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
-1 & -7 \\
2 & 4 \\
\end{pmatrix}
\end{aligned}
$$

Check by computing $AX$:

$$
\begin{aligned}
AX &=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
-1 & -7 \\
2 & 4 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
-1 + 4 & -7 + 8 \\
0 + 2 & 0 + 4 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix}
\end{aligned}
$$

Since $AX = B$, the solution is verified.