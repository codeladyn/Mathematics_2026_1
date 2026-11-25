### Exercise 13. Intersection of a Sphere and a Plane

## Question

Given the sphere

$$
x^2+y^2+z^2=25
$$

and the plane $z=3$, find the equation of the intersection curve and its radius. Then describe what happens for $z=c$ depending on $c$.

## Solution

Substitute $z = 3$ into the sphere equation:

$$
x^2 + y^2 + 3^2 = 25 \implies x^2 + y^2 = 16
$$

The intersection curve is a circle in the plane $z = 3$ centered at $(0, 0, 3)$ with radius $r = \sqrt{16} = 4$.

For a general horizontal plane $z = c$, we get $x^2 + y^2 = 25 - c^2$:
- **$|c| < 5$:** The intersection is a circle of radius $\sqrt{25 - c^2}$ (largest at $c = 0$ with radius $5$).
- **$|c| = 5$:** The plane is tangent to the sphere at a single point: $(0, 0, 5)$ or $(0, 0, -5)$.
- **$|c| > 5$:** $25 - c^2 < 0$, so there is no intersection (the plane misses the sphere completely).