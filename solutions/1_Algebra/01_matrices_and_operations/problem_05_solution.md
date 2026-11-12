### Exercise 5. Matrix Times Vector

## Question

Let the matrix and vector be given as:

$$
A=
\begin{pmatrix}
2 & -1 \\
1 & 3 \\
\end{pmatrix},\qquad x=
\begin{pmatrix}
4 \\
2 \\
\end{pmatrix}
$$

Compute $Ax$. Then express $Ax$ as a linear combination of the columns of $A$, with coefficients coming from the vector $x$.

## Solution

$$
\begin{aligned}
Ax &=
\begin{pmatrix}
2(4) + (-1)(2) \\
1(4) + 3(2) \\
\end{pmatrix} \\
&=
\begin{pmatrix}
6 \\
10 \\
\end{pmatrix}
\end{aligned}
$$

Written as a linear combination of the columns of $A$:

$$
\begin{aligned}
Ax &=
4
\begin{pmatrix}
2 \\
1 \\
\end{pmatrix}
+
2
\begin{pmatrix}
-1 \\
3 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
8 \\
4 \\
\end{pmatrix}
+
\begin{pmatrix}
-2 \\
6 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
6 \\
10 \\
\end{pmatrix}
\end{aligned}
$$

Multiplying a matrix by a column vector is just a shortcut for taking the columns of the matrix, multiplying each one by a number from the vector, and adding them all together.