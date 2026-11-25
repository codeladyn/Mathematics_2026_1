### Exercise 2. A Line in Space

## Question

Given the line:

$$
L:(x,y,z)=(2,-1,3)+t(1,2,-2)
$$

State a point on the line and its direction vector, check whether $P=(4,3,-1)$ lies on $L$, and find the point corresponding to $t=-1$.

## Solution

From the parametric form $(x,y,z) = p + tv$:
- A point on the line is $A = (2, -1, 3)$.
- The direction vector is $v = (1, 2, -2)$.

To check if $P=(4,3,-1)$ lies on $L$, set each coordinate equal to the parametric equations and solve for $t$:

$$
\begin{cases}
2 + t = 4 \implies t = 2, \\
-1 + 2t = 3 \implies 2t = 4 \implies t = 2, \\
3 - 2t = -1 \implies -2t = -4 \implies t = 2.
\end{cases}
$$

Because all three equations give the same value $t = 2$, the point $P=(4,3,-1)$ **does** lie on $L$.

For $t = -1$, substitute into the line equation:

$$
(x, y, z) = (2, -1, 3) + (-1)(1, 2, -2) = (2-1,\, -1-2,\, 3+2) = (1, -3, 5)
$$

The point corresponding to $t=-1$ is $(1, -3, 5)$.