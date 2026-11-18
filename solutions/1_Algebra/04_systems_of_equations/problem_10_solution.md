### Exercise 10. A Polynomial Through Three Points

## Question

Find a polynomial $p(x)=ax^2+bx+c$ whose graph passes through $(0,1)$, $(1,3)$, and $(2,9)$. Reduce the problem to a system of equations and check the result by substituting all three points.

## Solution

Substitute each point $(x, p(x))$ into $p(x) = ax^2 + bx + c$:
- For $(0, 1)$: $a(0)^2 + b(0) + c = 1 \implies c = 1$
- For $(1, 3)$: $a(1)^2 + b(1) + c = 3 \implies a + b + c = 3$
- For $(2, 9)$: $a(2)^2 + b(2) + c = 9 \implies 4a + 2b + c = 9$

This gives the linear system:

$$
\begin{cases}
c = 1, \\
a + b + c = 3, \\
4a + 2b + c = 9.
\end{cases}
$$

Substitute $c = 1$ into the second and third equations:
- $a + b = 2$
- $4a + 2b = 8 \implies 2a + b = 4$

Subtract the first from the second: $(2a + b) - (a + b) = 4 - 2 \implies a = 2$.
Then $2 + b = 2 \implies b = 0$.

The polynomial is:

$$
p(x) = 2x^2 + 1
$$

Verification:
- $p(0) = 2(0)^2 + 1 = 1$ (matches $(0, 1)$)
- $p(1) = 2(1)^2 + 1 = 3$ (matches $(1, 3)$)
- $p(2) = 2(2)^2 + 1 = 9$ (matches $(2, 9)$)