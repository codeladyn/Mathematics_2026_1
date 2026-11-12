### Exercise 13. A Recurrence Written in Matrix Form

## Question

Let the matrix be:

$$
F=
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix}
$$

Compute $F^2$, $F^3$, $F^4$, and $F^5$. Compare the numbers obtained with the sequence $0, 1, 1, 2, 3, 5, 8, \ldots$ and describe the relationship you observe. Then compute:

$$
F
\begin{pmatrix}
a \\
b \\
\end{pmatrix}
$$

Explain how this multiplication performs one recurrence step.

## Solution

$$
\begin{aligned}
F^2 &=
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix}
\end{aligned}
$$

$$
\begin{aligned}
F^3 &=
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
3 & 2 \\
2 & 1 \\
\end{pmatrix}
\end{aligned}
$$

$$
\begin{aligned}
F^4 &=
\begin{pmatrix}
3 & 2 \\
2 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
5 & 3 \\
3 & 2 \\
\end{pmatrix}
\end{aligned}
$$

$$
\begin{aligned}
F^5 &=
\begin{pmatrix}
5 & 3 \\
3 & 2 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
8 & 5 \\
5 & 3 \\
\end{pmatrix}
\end{aligned}
$$

The numbers in the matrices are exactly the numbers from the Fibonacci sequence ($0, 1, 1, 2, 3, 5, 8, \ldots$).

Multiplying by a general vector gives:

$$
\begin{aligned}
F
\begin{pmatrix}
a \\
b \\
\end{pmatrix}
&=
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix}
\begin{pmatrix}
a \\
b \\
\end{pmatrix} \\
&=
\begin{pmatrix}
a+b \\
a \\
\end{pmatrix}
\end{aligned}
$$

The matrix $F$ acts like a little machine for the Fibonacci sequence. When you feed it a vector with two numbers, it adds them together to make the new top number ($a+b$), and moves the old top number to the bottom ($a$) so it's ready for the next round.