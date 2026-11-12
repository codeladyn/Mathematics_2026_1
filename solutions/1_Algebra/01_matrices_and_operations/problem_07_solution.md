### Exercise 7. Identity Matrix, Zero Matrix, and Powers

## Question

For the matrix:

$$
A=
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}
$$

Compute $AI$, $IA$, $A+0$, $A^2$, and $A^3$. 
Explain the roles of the matrices $I$ and $0$, and describe the pattern you observe in successive powers of $A$.

## Solution

$$
AI =
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}
= A
$$

$$
IA =
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}
= A
$$

$$
A+0 =
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}
= A
$$

$$
\begin{aligned}
A^2 &=
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
4 & 4 \\
0 & 4 \\
\end{pmatrix}
\end{aligned}
$$

$$
\begin{aligned}
A^3 &= A^2 A \\
&=
\begin{pmatrix}
4 & 4 \\
0 & 4 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
8 & 12 \\
0 & 8 \\
\end{pmatrix}
\end{aligned}
$$

The identity matrix $I$ acts like the number 1 in normal multiplication (multiplying by it changes nothing), and the zero matrix acts like the number 0 in addition (adding it changes nothing). 

When finding the successive powers of $A$, a specific pattern emerges:
- The main diagonal values double each time ($2, 4, 8$), representing $2^n$.
- The upper-right entries grow in the sequence $1, 4, 12$. These follow the pattern $n \cdot 2^{n-1}$.