### Exercise 9. Composing Transformations

## Question

Let:

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad R=
\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix}
$$

The matrix $S$ describes nonuniform scaling, while $R$ describes a $90^\circ$ counterclockwise rotation.
For the vector:

$$
x=
\begin{pmatrix}
1 \\
2 \\
\end{pmatrix}
$$

Compute $RSx$ and $SRx$. Compare the results and explain geometrically why the order of these transformations matters.

## Solution

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

The results are totally different. Matrix multiplication is doing one visual transformation after another, and order matters! Stretching a shape and then rotating it ($RSx$) gives you a different result than rotating it first and then stretching the new shape ($SRx$).