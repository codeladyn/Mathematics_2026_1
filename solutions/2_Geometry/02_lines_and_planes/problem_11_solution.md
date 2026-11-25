### Exercise 11. Plane Containing a Line and a Point

## Question

Find the equation of the plane containing:

$$
(x,y,z)=(1,0,2)+t(1,1,-1)
$$

and the point $P=(0,2,1)$. Check that both the entire line and the point lie in the plane you obtain.

## Solution

The line passes through $Q=(1,0,2)$ and has direction vector $v_1 = (1, 1, -1)$. Construct a second direction vector in the plane from $Q$ to $P$:

$$
v_2 = \overrightarrow{QP} = (0 - 1,\, 2 - 0,\, 1 - 2) = (-1, 2, -1)
$$

Compute a normal vector $n$ using the cross product $v_1 \times v_2$:

$$
\begin{aligned}
n &= (1(-1) - (-1)(2),\, -(1(-1) - (-1)(-1)),\, 1(2) - 1(-1)) \\
&= (-1 + 2,\, -(-1 - 1),\, 2 + 1) \\
&= (1, 2, 3)
\end{aligned}
$$

Using $n=(1,2,3)$ and point $Q=(1,0,2)$:

$$
\begin{aligned}
1(x - 1) + 2(y - 0) + 3(z - 2) &= 0 \\
x + 2y + 3z - 7 &= 0
\end{aligned}
$$

The plane equation is $x + 2y + 3z = 7$.

Verification:
- For the entire line $(1+t, t, 2-t)$: $(1+t) + 2(t) + 3(2-t) = 1 + 6 + (1 + 2 - 3)t = 7$ (holds for all $t$).
- For the point $P=(0,2,1)$: $0 + 2(2) + 3(1) = 7$ (true).