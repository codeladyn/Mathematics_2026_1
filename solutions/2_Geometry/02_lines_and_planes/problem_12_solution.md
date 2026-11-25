### Exercise 12. Intersection Line of Two Planes

## Question

Find a parametric equation of the line that is the intersection of:

$$
x+y+z=3,\qquad x-y+z=1.
$$

Find its direction vector in two ways: from the system of equations and from the cross product of the normal vectors. Compare the results.

## Solution

Method 1 (From the system of equations):

Subtract the second equation from the first:

$$
(x + y + z) - (x - y + z) = 3 - 1 \implies 2y = 2 \implies y = 1
$$

Substitute $y = 1$ into the first equation:

$$
x + 1 + z = 3 \implies x = 2 - z
$$

Let $z = t$ (free variable). Then the parametric equation of the intersection line is:

$$
(x, y, z) = (2 - t,\, 1,\, t) = (2, 1, 0) + t(-1, 0, 1)
$$

This gives the direction vector $v_1 = (-1, 0, 1)$.

Method 2 (From the cross product of the normals):

The normal vectors are $n_1 = (1, 1, 1)$ and $n_2 = (1, -1, 1)$. Their cross product is:

$$
\begin{aligned}
v_2 = n_1 \times n_2 &= (1(1) - 1(-1),\, -(1(1) - 1(1)),\, 1(-1) - 1(1)) \\
&= (2, 0, -2)
\end{aligned}
$$

Comparison: Notice that $v_2 = (2, 0, -2) = -2(-1, 0, 1) = -2v_1$. Because one vector is a nonzero scalar multiple of the other, both methods describe the exact same line direction.