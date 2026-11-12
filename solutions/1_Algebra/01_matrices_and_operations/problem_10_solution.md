### Exercise 10. Columns of a Matrix Product

## Question

Given the matrices:

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & 2 \\
-1 & 0 \\
3 & 1 \\
\end{pmatrix}
$$

Denote the columns of $B$ by $b_1,b_2$.
1. Compute $Ab_1$ and $Ab_2$.
2. Compute the matrix $AB$.
3. Compare the results and explain why the columns of $AB$ are exactly the vectors $Ab_1$ and $Ab_2$.

## Solution

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

Multiplying two matrices together is structurally just taking the first matrix ($A$), multiplying it by each individual column vector of the second matrix ($B$) one by one, and sticking those answers next to each other to build the new matrix.