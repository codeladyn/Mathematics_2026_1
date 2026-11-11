### Exercise 6. Transpose

**Result**

$$
A^T =
\begin{pmatrix}
1 & 4 \\
2 & 5 \\
3 & 6 \\
\end{pmatrix}
$$

$$
B^T =
\begin{pmatrix}
1 & 2 & -1 \\
0 & 1 & 3 \\
\end{pmatrix}
$$

$$
\begin{aligned}
AB &=
\begin{pmatrix}
1(1)+2(2)+3(-1) & 1(0)+2(1)+3(3) \\
4(1)+5(2)+6(-1) & 4(0)+5(1)+6(3) \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2 & 11 \\
8 & 23 \\
\end{pmatrix}
\end{aligned}
$$

Transposing the product gives:

$$
(AB)^T =
\begin{pmatrix}
2 & 8 \\
11 & 23 \\
\end{pmatrix}
$$

Multiplying the transposes in reverse order gives:

$$
\begin{aligned}
B^T A^T &=
\begin{pmatrix}
1 & 2 & -1 \\
0 & 1 & 3 \\
\end{pmatrix}
\begin{pmatrix}
1 & 4 \\
2 & 5 \\
3 & 6 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1+4-3 & 4+10-6 \\
0+2+9 & 0+5+18 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2 & 8 \\
11 & 23 \\
\end{pmatrix}
\end{aligned}
$$

**Explanation**

To transpose a matrix, you just swap its rows and columns. This exercise shows a cool rule: if you multiply two matrices and then transpose the answer, it's the exact same as transposing them first and multiplying them in reverse order.