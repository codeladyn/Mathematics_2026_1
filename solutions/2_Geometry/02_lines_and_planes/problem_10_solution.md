### Exercise 10. Projection of a Point onto a Plane

## Question

Find the orthogonal projection of $P=(2,1,3)$ onto the plane $x+y+z=3$, and then find the reflection of $P$ across this plane. Check that the midpoint of the segment joining the point and its reflection lies on the plane.

## Solution

The normal vector of the plane $x + y + z = 3$ is $n = (1, 1, 1)$. The line passing through $P=(2,1,3)$ perpendicular to the plane is:

$$
(x, y, z) = (2 + t,\, 1 + t,\, 3 + t)
$$

Find where this line hits the plane by substituting into $x + y + z = 3$:

$$
\begin{aligned}
(2 + t) + (1 + t) + (3 + t) &= 3 \\
6 + 3t &= 3 \\
3t &= -3 \\
t &= -1
\end{aligned}
$$

The orthogonal projection $P'$ corresponds to $t = -1$:

$$
P' = (2 - 1,\, 1 - 1,\, 3 - 1) = (1, 0, 2)
$$

To find the reflection $P''$, travel the same step again past the plane (which corresponds to $t = -2$):

$$
P'' = (2 - 2,\, 1 - 2,\, 3 - 2) = (0, -1, 1)
$$

Check the midpoint $M$ of $P=(2,1,3)$ and $P''=(0,-1,1)$:

$$
M = \left(\frac{2+0}{2},\, \frac{1+(-1)}{2},\, \frac{3+1}{2}\right) = (1, 0, 2)
$$

The midpoint is $P'=(1,0,2)$, and substituting it into the plane gives $1 + 0 + 2 = 3$, confirming it lies on the plane.