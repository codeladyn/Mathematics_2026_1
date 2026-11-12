### Exercise 12. Formula for a Matrix Power

## Question

Let the matrix be:

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
$$

Compute $A^2$, $A^3$, and $A^4$, and use them to formulate a conjecture for $A^n$. Then assume the formula is true for $n$, multiply by $A$, and explain why you obtain exactly the formula for $n+1$.

## Solution

Compute $A^2$:

$$
\begin{aligned}
A^2 &=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

Compute $A^3$:

$$
\begin{aligned}
A^3 &=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 3 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

Compute $A^4$:

$$
\begin{aligned}
A^4 &=
\begin{pmatrix}
1 & 3 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 4 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

Conjecture for $A^n$:

$$
A^n=
\begin{pmatrix}
1 & n \\
0 & 1 \\
\end{pmatrix}
$$

Now, assuming this formula is true for $n$, let's multiply by $A$ to find $A^{n+1}$:

$$
\begin{aligned}
A^{n+1} &= A^n A \\
&=
\begin{pmatrix}
1 & n \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1(1)+n(0) & 1(1)+n(1) \\
0(1)+1(0) & 0(1)+1(1) \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & n+1 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

By finding the first few powers, we see a clear pattern: the top-right number matches the power we are raising the matrix to. To prove it works forever (a method called mathematical induction), we just show that multiplying our guessed formula by one more $A$ perfectly gives us the formula for the next step, $n+1$.