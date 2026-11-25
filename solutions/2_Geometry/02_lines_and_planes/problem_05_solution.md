### Exercise 5. Relative Position of Two Lines

## Question

Analyze the position of:

$$
L_1:(x,y,z)=(1,1,0)+t(1,2,1),
$$

$$
L_2:(x,y,z)=(2,0,1)+s(0,1,-1).
$$

If they intersect, give the intersection point. If not, determine whether they are parallel or skew. Justify the classification.

## Solution

First, compare the direction vectors $v_1 = (1, 2, 1)$ and $v_2 = (0, 1, -1)$. Because the first coordinate of $v_2$ is $0$ while the first coordinate of $v_1$ is $1$, $v_1$ and $v_2$ are not scalar multiples of each other. Therefore, the lines are **not parallel**.

Next, test for an intersection by setting the coordinates equal:

$$
\begin{cases}
1 + t = 2, \\
1 + 2t = s, \\
t = 1 - s.
\end{cases}
$$

From the first equation, $t = 1$.
Substitute $t = 1$ into the second equation: $s = 1 + 2(1) = 3$.
Check the third equation with $t = 1$ and $s = 3$:

$$
1 = 1 - 3 \implies 1 = -2
$$

This is a contradiction, so the lines do not intersect. Because the lines are neither parallel nor intersecting, they are **skew lines**.