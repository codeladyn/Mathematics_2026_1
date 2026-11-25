### Exercise 8. Intersection Point of a Line and a Plane

## Question

Find the intersection point of:

$$
(x,y,z)=(1,0,2)+t(1,2,-1)
$$

with the plane $x+y+z=4$. Check the result by substituting it into both descriptions.

## Solution

Write the coordinates of a general point on the line:

$$
x = 1 + t,\qquad y = 2t,\qquad z = 2 - t
$$

Substitute these into the plane equation $x + y + z = 4$:

$$
\begin{aligned}
(1 + t) + 2t + (2 - t) &= 4 \\
3 + 2t &= 4 \\
2t &= 1 \\
t &= \frac{1}{2}
\end{aligned}
$$

Substitute $t = \frac{1}{2}$ back into the line equation to find the intersection point:

$$
(x, y, z) = \left(1 + \frac{1}{2},\, 2\left(\frac{1}{2}\right),\, 2 - \frac{1}{2}\right) = \left(\frac{3}{2}, 1, \frac{3}{2}\right)
$$

Verification:
- In the line: setting $t = \frac{1}{2}$ gives $(1,0,2) + \frac{1}{2}(1,2,-1) = \left(\frac{3}{2}, 1, \frac{3}{2}\right)$ (true).
- In the plane: $\frac{3}{2} + 1 + \frac{3}{2} = 4$ (true).