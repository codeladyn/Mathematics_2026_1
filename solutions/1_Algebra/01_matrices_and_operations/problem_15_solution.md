### Exercise 15. Associativity of Multiplication and Different Calculation Paths

## Question

Given the matrices:

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\quad B=
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix},\quad C=
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix}
$$

Compute $(AB)C$ and $A(BC)$. Compare the results and the number of intermediate operations. Explain what associativity of matrix multiplication means in this example.

## Solution

Path 1: Compute $(AB)C$

$$
\begin{aligned}
AB &=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
5 & 2 \\
1 & 4 \\
\end{pmatrix}
\end{aligned}
$$

$$
\begin{aligned}
(AB)C &=
\begin{pmatrix}
5 & 2 \\
1 & 4 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
10 & 3 \\
2 & -3 \\
\end{pmatrix}
\end{aligned}
$$

Path 2: Compute $A(BC)$

$$
\begin{aligned}
BC &=
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2 & 1 \\
4 & 1 \\
-2 & -4 \\
\end{pmatrix}
\end{aligned}
$$

$$
\begin{aligned}
A(BC) &=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
4 & 1 \\
-2 & -4 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2+8+0 & 1+2+0 \\
0+4-2 & 0+1-4 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
10 & 3 \\
2 & -3 \\
\end{pmatrix}
\end{aligned}
$$

Both calculation paths give you the exact same final matrix. Associativity basically means that as long as you keep the matrices in the same left-to-right order ($A$, then $B$, then $C$), it doesn't matter if you choose to group $AB$ together first or $BC$ together first. The final answer will always match, even if the math steps in the middle look completely different.