### Exercise 7. Inverse of a Product

## Question

For the matrices:

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
2 & 0 \\
0 & 3 \\
\end{pmatrix}
$$

Compute $(AB)^{-1}$ and $B^{-1}A^{-1}$. Check that the results are the same and explain the meaning of the reversed order.

## Solution

First, compute $AB$:

$$
AB =
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
2 & 0 \\
0 & 3 \\
\end{pmatrix}
=
\begin{pmatrix}
2 & 3 \\
0 & 3 \\
\end{pmatrix}
$$

Its determinant is $\det(AB) = 2(3) - 3(0) = 6$, so:

$$
(AB)^{-1} = \frac{1}{6}
\begin{pmatrix}
3 & -3 \\
0 & 2 \\
\end{pmatrix}
=
\begin{pmatrix}
\frac{1}{2} & -\frac{1}{2} \\
0 & \frac{1}{3} \\
\end{pmatrix}
$$

Next, find $A^{-1}$ and $B^{-1}$ separately:

$$
A^{-1} =
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix},\qquad B^{-1} =
\begin{pmatrix}
\frac{1}{2} & 0 \\
0 & \frac{1}{3} \\
\end{pmatrix}
$$

Multiply them in reverse order:

$$
\begin{aligned}
B^{-1}A^{-1} &=
\begin{pmatrix}
\frac{1}{2} & 0 \\
0 & \frac{1}{3} \\
\end{pmatrix}
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
\frac{1}{2} & -\frac{1}{2} \\
0 & \frac{1}{3} \\
\end{pmatrix}
\end{aligned}
$$

The results are identical. The order reverses because to undo two steps done in a row (first $B$, then $A$), you have to undo the last step ($A$) first, and then undo the first step ($B$).