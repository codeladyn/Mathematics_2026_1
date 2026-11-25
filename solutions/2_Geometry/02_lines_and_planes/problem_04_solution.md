### Exercise 4. Plane Through Three Points

## Question

Find the equation of the plane through:

$$
A=(1,0,0),\quad B=(0,1,0),\quad C=(0,0,1).
$$

First construct two vectors lying in the plane, and then use the cross product. Check the resulting equation on all three points.

## Solution

Construct two vectors in the plane starting from $A$:

$$
\overrightarrow{AB} = (-1, 1, 0),\qquad \overrightarrow{AC} = (-1, 0, 1)
$$

Take their cross product to find a normal vector $n$:

$$
\begin{aligned}
n = \overrightarrow{AB}\times\overrightarrow{AC} &= (1(1) - 0(0),\, -((-1)(1) - 0(-1)),\, (-1)(0) - 1(-1)) \\
&= (1, 1, 1)
\end{aligned}
$$

Using $n=(1,1,1)$ and point $A=(1,0,0)$:

$$
\begin{aligned}
1(x - 1) + 1(y - 0) + 1(z - 0) &= 0 \\
x + y + z &= 1
\end{aligned}
$$

Check all three points in $x + y + z = 1$:
- $A=(1,0,0)$: $1 + 0 + 0 = 1$ (true).
- $B=(0,1,0)$: $0 + 1 + 0 = 1$ (true).
- $C=(0,0,1)$: $0 + 0 + 1 = 1$ (true).