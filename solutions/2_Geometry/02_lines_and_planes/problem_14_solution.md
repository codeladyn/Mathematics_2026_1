### Exercise 14. Contrast: Intersection and Parallelism

## Question

From the point $P=(0,0,1)$, two lines are drawn with direction vectors:

$$
v_1=(2,1,-1),\qquad v_2=(2,1,0).
$$

For each line, analyze its position relative to the plane $z=0$.
For the line that intersects the plane, find the intersection point. For the other line, explain how you can recognize parallelism without solving an equation.

## Solution

The plane $z = 0$ has normal vector $n = (0, 0, 1)$.

- **Line 1** ($v_1 = (2, 1, -1)$):
  Check $v_1 \cdot n = -1 \neq 0$, so the line **intersects** the plane at one point.
  The parametric equation is $(x, y, z) = (2t, t, 1 - t)$.
  Setting $z = 0$ gives $1 - t = 0 \implies t = 1$.
  The intersection point is $(2(1), 1, 0) = (2, 1, 0)$.

- **Line 2** ($v_2 = (2, 1, 0)$):
  The third coordinate of $v_2$ is $0$, so $v_2 \cdot n = 0$. Without solving any equation, we can immediately see that moving along $v_2$ never changes the $z$-coordinate—it stays permanently fixed at height $z = 1$. Therefore, Line 2 is **parallel** to the plane $z = 0$ and never intersects it.