### Exercise 9. Composing Transformations

**Result**

First, compute $RSx$:

$$
\begin{aligned}
Sx &=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 \\
2 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2 \\
2 \\
\end{pmatrix}
\end{aligned}
$$

$$
\begin{aligned}
R(Sx) &=
\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix}
\begin{pmatrix}
2 \\
2 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
-2 \\
2 \\
\end{pmatrix}
\end{aligned}
$$

Next, compute $SRx$:

$$
\begin{aligned}
Rx &=
\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix}
\begin{pmatrix}
1 \\
2 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
-2 \\
1 \\
\end{pmatrix}
\end{aligned}
$$

$$
\begin{aligned}
S(Rx) &=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
-2 \\
1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
-4 \\
1 \\
\end{pmatrix}
\end{aligned}
$$

**Explanation**

Matrix multiplication is just doing one visual transformation after another. Order matters! Stretching a shape and then rotating it gives you a totally different result than rotating it first and then stretching it.