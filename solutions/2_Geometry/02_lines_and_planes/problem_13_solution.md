### Exercise 13. Closest Point on a Plane

## Question

Find the point on the plane $x+2y+2z=4$ closest to $P=(3,0,0)$. Give the distance and check that the segment joining the two points is perpendicular to the plane.

## Solution

The normal vector of the plane is $n = (1, 2, 2)$. The line from $P=(3,0,0)$ moving straight toward the plane along $n$ is:

$$
(x, y, z) = (3 + t,\, 2t,\, 2t)
$$

Substitute into the plane equation $x + 2y + 2z = 4$:

$$
\begin{aligned}
(3 + t) + 2(2t) + 2(2t) &= 4 \\
3 + 9t &= 4 \\
9t &= 1 \\
t &= \frac{1}{9}
\end{aligned}
$$

The closest point $Q$ is:

$$
Q = \left(3 + \frac{1}{9},\, \frac{2}{9},\, \frac{2}{9}\right) = \left(\frac{28}{9}, \frac{2}{9}, \frac{2}{9}\right)
$$

The vector from $P$ to $Q$ is:

$$
\overrightarrow{PQ} = \left(\frac{1}{9}, \frac{2}{9}, \frac{2}{9}\right)
$$

The distance is the length of $\overrightarrow{PQ}$:

$$
d = \|\overrightarrow{PQ}\| = \sqrt{\left(\frac{1}{9}\right)^2 + \left(\frac{2}{9}\right)^2 + \left(\frac{2}{9}\right)^2} = \sqrt{\frac{1 + 4 + 4}{81}} = \sqrt{\frac{9}{81}} = \frac{1}{3}
$$

Check perpendicularity: $\overrightarrow{PQ} = \frac{1}{9}(1, 2, 2) = \frac{1}{9}n$. Because $\overrightarrow{PQ}$ is a scalar multiple of the plane's normal vector $n$, the segment $PQ$ is perpendicular to the plane.