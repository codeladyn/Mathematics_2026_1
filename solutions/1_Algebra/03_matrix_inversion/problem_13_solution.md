### Exercise 13. Undoing a Composite Transformation

## Question

The matrices:

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad H=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
$$

describe nonuniform scaling and shear. For $T=HS$, find $T^{-1}$ in two ways:
1. first compute $T$, then its inverse,
2. use $(HS)^{-1}=S^{-1}H^{-1}$.

Compare the results. Additionally compute $H^{-1}S^{-1}$ and verify that the incorrect order gives a different matrix. Explain the rule: "when undoing a composition of operations, we undo them from the end."

## Solution

Method 1: First compute $T = HS$:

$$
T =
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix}
=
\begin{pmatrix}
2 & 1 \\
0 & 1 \\
\end{pmatrix}
$$

Since $\det T = 2$, its inverse is:

$$
T^{-1} = \frac{1}{2}
\begin{pmatrix}
1 & -1 \\
0 & 2 \\
\end{pmatrix}
=
\begin{pmatrix}
\frac{1}{2} & -\frac{1}{2} \\
0 & 1 \\
\end{pmatrix}
$$

Method 2: Find $S^{-1}$ and $H^{-1}$ first:

$$
S^{-1}=
\begin{pmatrix}
\frac{1}{2} & 0 \\
0 & 1 \\
\end{pmatrix},\qquad H^{-1}=
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix}
$$

Multiply as $S^{-1}H^{-1}$:

$$
S^{-1}H^{-1} =
\begin{pmatrix}
\frac{1}{2} & 0 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix}
=
\begin{pmatrix}
\frac{1}{2} & -\frac{1}{2} \\
0 & 1 \\
\end{pmatrix}
$$

Both methods give the exact same matrix.

Now compute the incorrect order $H^{-1}S^{-1}$:

$$
H^{-1}S^{-1} =
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
\frac{1}{2} & 0 \\
0 & 1 \\
\end{pmatrix}
=
\begin{pmatrix}
\frac{1}{2} & -1 \\
0 & 1 \\
\end{pmatrix}
$$

This is clearly different from $T^{-1}$. When $T = HS$ acts on a vector, $S$ is applied first and $H$ is applied second. To undo the whole process, you have to undo the last thing that happened ($H$) first, and then undo the first thing ($S$).