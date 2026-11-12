### Exercise 11. When Do Matrices Commute?

## Question

Given the matrices:

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix}
$$

Find the conditions on $a, b, c$, and $d$ under which $AB = BA$. Describe the general form of all such matrices $B$.

## Solution

First, compute the product $AB$:

$$
\begin{aligned}
AB &=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix} \\
&=
\begin{pmatrix}
a+c & b+d \\
c & d \\
\end{pmatrix}
\end{aligned}
$$

Next, compute the product $BA$:

$$
\begin{aligned}
BA &=
\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
a & a+b \\
c & c+d \\
\end{pmatrix}
\end{aligned}
$$

For $AB = BA$ to be true, every single position in the matrices must match exactly:
1. Top-left: $a+c = a$, which means $c = 0$.
2. Bottom-left: $c = c$ (this is always true).
3. Bottom-right: $d = c+d$, which means $0 = c$, matching the first step.
4. Top-right: $b+d = a+b$, which means $d = a$.

Using these conditions ($c=0$ and $d=a$), the general form of all such matrices $B$ is:

$$
B=
\begin{pmatrix}
a & b \\
0 & a \\
\end{pmatrix}
$$

To make two matrices commute (meaning order doesn't matter when multiplying), we just set their multiplication answers equal to each other and solve the mini-equations. For this specific matrix $A$, any matrix $B$ will commute with it as long as the bottom-left number is 0 and the two diagonal numbers are the same.