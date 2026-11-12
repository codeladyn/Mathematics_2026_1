### Exercise 14. Rotation Matrices

## Question

The matrix for a rotation through an angle $\theta$ is:

$$
R(\theta)=
\begin{pmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta \\
\end{pmatrix}
$$

Compute $R(\alpha)R(\beta)$ and, using the angle-sum formulas for sine and cosine, show that $R(\alpha)R(\beta)=R(\alpha+\beta)$. Explain the result geometrically.

## Solution

Multiply the two matrices:

$$
\begin{aligned}
R(\alpha)R(\beta) &=
\begin{pmatrix}
\cos\alpha & -\sin\alpha \\
\sin\alpha & \cos\alpha \\
\end{pmatrix}
\begin{pmatrix}
\cos\beta & -\sin\beta \\
\sin\beta & \cos\beta \\
\end{pmatrix} \\
&=
\begin{pmatrix}
\cos\alpha\cos\beta - \sin\alpha\sin\beta & -\cos\alpha\sin\beta - \sin\alpha\cos\beta \\
\sin\alpha\cos\beta + \cos\alpha\sin\beta & -\sin\alpha\sin\beta + \cos\alpha\cos\beta \\
\end{pmatrix}
\end{aligned}
$$

We use the standard trigonometry angle-sum formulas:
- $\cos(\alpha+\beta) = \cos\alpha\cos\beta - \sin\alpha\sin\beta$
- $\sin(\alpha+\beta) = \sin\alpha\cos\beta + \cos\alpha\sin\beta$

Replacing the messy parts of our matrix with these simple identities gives:

$$
\begin{aligned}
R(\alpha)R(\beta) &=
\begin{pmatrix}
\cos(\alpha+\beta) & -\sin(\alpha+\beta) \\
\sin(\alpha+\beta) & \cos(\alpha+\beta) \\
\end{pmatrix} \\
&= R(\alpha+\beta)
\end{aligned}
$$

Geometrically, this makes total sense. If you rotate an object by angle $\beta$ and then rotate it again by angle $\alpha$, you could have saved time and just rotated it by the combined angle ($\alpha + \beta$) in a single step.