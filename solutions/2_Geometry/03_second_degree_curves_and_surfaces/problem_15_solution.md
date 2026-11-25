### Exercise 15. Recognition and Sketch Without a Given Name

## Question

Consider the two equations:

$$
4x^2+9y^2-8x+36y+4=0,
$$

$$
4x^2+y^2=z^2.
$$

For the first equation, reduce it to canonical form, recognize the curve, give its most important features, and make a sketch.

For the second equation, do not begin by using a ready-made name for the surface. First describe the cross-sections $z=c$ and the cross-sections by the planes $x=0$ and $y=0$, paying attention to the different scales along the axes. Only then identify the surface and make a sketch.

## Solution

**Part 1: $4x^2 + 9y^2 - 8x + 36y + 4 = 0$**

Complete the square:

$$
\begin{aligned}
4(x^2 - 2x) + 9(y^2 + 4y) &= -4 \\
4((x - 1)^2 - 1) + 9((y + 2)^2 - 4) &= -4 \\
4(x - 1)^2 - 4 + 9(y + 2)^2 - 36 &= -4 \\
4(x - 1)^2 + 9(y + 2)^2 &= 36
\end{aligned}
$$

Divide by $36$:

$$
\frac{(x - 1)^2}{9} + \frac{(y + 2)^2}{4} = 1
$$

- **Curve:** Shifted **ellipse**.
- **Features:** Center at $(1, -2)$, horizontal semiaxis $a = 3$, vertical semiaxis $b = 2$.
- **Sketch:** A horizontal oval centered at $(1, -2)$ reaching from $x = -2$ to $x = 4$ and from $y = -4$ to $y = 0$.

**Part 2: $4x^2 + y^2 = z^2$**

- **Cross-sections $z = c$:** $4x^2 + y^2 = c^2$.
  - For $c = 0$, this is the single point $(0, 0, 0)$.
  - For $c \neq 0$, dividing by $c^2$ gives:

$$
\frac{x^2}{(c/2)^2} + \frac{y^2}{c^2} = 1
$$

  These are ellipses centered on the $z$-axis whose semiaxis along $y$ ($|c|$) is twice as long as the semiaxis along $x$ ($\frac{|c|}{2}$). Both semiaxes grow linearly with $|c|$.
- **Cross-section $x = 0$:** $y^2 = z^2 \implies z = \pm y$ (two straight lines with slopes $\pm 1$).
- **Cross-section $y = 0$:** $4x^2 = z^2 \implies z = \pm 2x$ (two steeper straight lines with slopes $\pm 2$).

- **Identification:** This surface is an **elliptic cone** with vertex at the origin, opening along the $z$-axis, stretched twice as wide along the $y$-axis as along the $x$-axis.
- **Sketch:** A double cone meeting at $(0,0,0)$ whose horizontal slices are ovals (elongated along the $y$-axis) rather than circles.