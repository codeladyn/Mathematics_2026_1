### Exercise 1. Line Through Two Points

## Question

Find the equation of the line through $A=(1,2)$ and $B=(4,-1)$ in parametric and general form. Identify a direction vector and an example of a normal vector. Check that both points satisfy the equation you obtain.

## Solution

First, find a direction vector $v$ by subtracting $A$ from $B$:

$$
v = \overrightarrow{AB} = (4-1,\, -1-2) = (3, -3)
$$

Using point $A=(1,2)$ and direction vector $v=(3,-3)$, the parametric form of the line is:

$$
(x, y) = (1, 2) + t(3, -3)
$$

A normal vector $n$ must be perpendicular to $v$ (so $n\cdot v = 0$). A simple choice is:

$$
n = (1, 1)
$$

since $1(3) + 1(-3) = 0$.

Using the point-normal form $n\cdot((x,y) - A) = 0$:

$$
\begin{aligned}
1(x - 1) + 1(y - 2) &= 0 \\
x + y - 3 &= 0
\end{aligned}
$$

The general form is $x + y - 3 = 0$.

Check both points in the general equation:
- For $A=(1,2)$: $1 + 2 - 3 = 0$ (true).
- For $B=(4,-1)$: $4 + (-1) - 3 = 0$ (true).