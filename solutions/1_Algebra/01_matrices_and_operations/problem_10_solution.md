### Exercise 10. Columns of a Matrix Product

**Result**

$$
\begin{aligned}
Ab_1 &=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 \\
-1 \\
3 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1-2+0 \\
0-1+3 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
-1 \\
2 \\
\end{pmatrix}
\end{aligned}
$$

$$
\begin{aligned}
Ab_2 &=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix}
\begin{pmatrix}
2 \\
0 \\
1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2+0+0 \\
0+0+1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2 \\
1 \\
\end{pmatrix}
\end{aligned}
$$

Computing the full product $AB$:

$$
\begin{aligned}
AB &=
\begin{pmatrix}
1(1)+2(-1)+0(3) & 1(2)+2(0)+0(1) \\
0(1)+1(-1)+1(3) & 0(2)+1(0)+1(1) \\
\end{pmatrix} \\
&=
\begin{pmatrix}
-1 & 2 \\
2 & 1 \\
\end{pmatrix}
\end{aligned}
$$

**Explanation**

Multiplying two matrices together is really just taking the first matrix, multiplying it by each column of the second matrix one by one, and sticking those answers next to each other to build the new matrix.