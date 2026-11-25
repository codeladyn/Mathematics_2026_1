### Exercise 15. Complete Classification of a Line Relative to a Plane

## Question

Let:

$$
L:p+tv,\qquad \Pi:n\cdot x=d.
$$

State the conditions distinguishing the three cases: one intersection point, parallel with no common points, and the line contained in the plane. Then illustrate each case with your own simple numerical example.

## Solution

Substituting $x = p + tv$ into $n\cdot x = d$ gives the linear equation in $t$:

$$
(n\cdot v)t = d - n\cdot p
$$

This yields the three classification cases:
1. **One intersection point:** $n\cdot v \neq 0$. (There is a unique solution for $t$.)
2. **Parallel with no common points:** $n\cdot v = 0$ and $n\cdot p \neq d$. (The direction is parallel to the plane, and the starting point $p$ is not on the plane.)
3. **Line contained in the plane:** $n\cdot v = 0$ and $n\cdot p = d$. (The direction is parallel to the plane, and the starting point $p$ lies on the plane.)

**Simple numerical examples** (using the plane $\Pi: z = 0$, where $n = (0,0,1)$ and $d = 0$):
- **One intersection point:** $L: (0,0,1) + t(0,0,1)$. Here $n\cdot v = 1 \neq 0$ (intersects at $(0,0,0)$).
- **Parallel with no common points:** $L: (0,0,1) + t(1,0,0)$. Here $n\cdot v = 0$ and $n\cdot p = 1 \neq 0$.
- **Line contained in the plane:** $L: (0,0,0) + t(1,0,0)$. Here $n\cdot v = 0$ and $n\cdot p = 0 = d$.