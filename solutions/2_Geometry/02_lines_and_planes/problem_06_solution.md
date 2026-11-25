### Exercise 6. Angle Between Planes

## Question

Given the planes:

$$
\Pi_1:x+y+z=1,\qquad \Pi_2:x-y=2.
$$

First use the normal vectors to decide whether the planes are parallel. If not, compute the angle between them and explain why the normal vectors alone are enough for this calculation.

## Solution

Read the normal vectors from the coefficients of $x, y, z$:

$$
n_1 = (1, 1, 1),\qquad n_2 = (1, -1, 0)
$$

These vectors are not scalar multiples of each other, so the planes are **not parallel**.

Compute the dot product of the normal vectors:

$$
n_1\cdot n_2 = 1(1) + 1(-1) + 1(0) = 1 - 1 + 0 = 0
$$

Since $\cos\theta = \frac{|n_1\cdot n_2|}{\|n_1\|\,\|n_2\|} = 0$, the angle between the planes is $\theta = 90^\circ$ (the planes are perpendicular).

The normal vectors alone are enough because each normal is locked at a $90^\circ$ angle to its plane. Rotating a plane rotates its normal by the exact same angle, so the angle between the two planes is identical to the angle between their normals.