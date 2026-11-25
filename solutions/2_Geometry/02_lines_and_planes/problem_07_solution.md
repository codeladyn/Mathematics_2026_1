### Exercise 7. A Line Relative to a Plane

## Question

For:

$$
L:(x,y,z)=(1,1,0)+t(1,-1,0),\qquad \Pi:x+y+z=2,
$$

determine whether the line intersects the plane at one point, is parallel to it, or lies in it. Explain the role of the dot product of the direction vector and the normal vector.

## Solution

Identify the direction vector of $L$ and the normal vector of $\Pi$:

$$
v = (1, -1, 0),\qquad n = (1, 1, 1)
$$

Compute their dot product:

$$
v\cdot n = 1(1) + (-1)(1) + 0(1) = 1 - 1 + 0 = 0
$$

Because $v\cdot n = 0$, the line's direction is perpendicular to the plane's normal, which means the line is parallel to the plane (it either never touches it or lies completely inside it).

Check whether the starting point $P=(1,1,0)$ of $L$ lies on $\Pi$:

$$
1 + 1 + 0 = 2
$$

Since the point satisfies the plane equation, the entire line **lies in the plane**.