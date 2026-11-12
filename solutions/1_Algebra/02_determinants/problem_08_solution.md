### Exercise 8. Determinant of a Product

## Question

Let $A, B$ be square matrices such that $\det A=3$ and $\det B=-5$. 
Compute $\det(AB)$, $\det(BA)$ and, if it exists, $\det(A^{-1}B)$. 
Explain why the first two results are equal even though usually $AB\neq BA$.

## Solution

$$
\begin{aligned}
\det(AB) &= \det A \cdot \det B \\
&= 3(-5) \\
&= -15
\end{aligned}
$$

$$
\begin{aligned}
\det(BA) &= \det B \cdot \det A \\
&= -5(3) \\
&= -15
\end{aligned}
$$

$$
\begin{aligned}
\det(A^{-1}B) &= \det(A^{-1}) \cdot \det B \\
&= \frac{1}{\det A} \cdot \det B \\
&= \frac{1}{3} (-5) \\
&= -\frac{5}{3}
\end{aligned}
$$

While multiplying the actual matrices $A$ and $B$ depends on the order ($AB \neq BA$), the determinant is just a regular real number. Since regular number multiplication is commutative ($3 \times -5$ is the same as $-5 \times 3$), the determinant of their product is the same either way.