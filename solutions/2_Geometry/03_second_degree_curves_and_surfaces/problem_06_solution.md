### Exercise 6. Shifted Ellipse

## Question

Reduce

$$
4x^2+9y^2-16x+18y-11=0
$$

to canonical form. Give the center and semiaxis lengths. Check that substituting the coordinates of the center into the left-hand side gives a value consistent with the form you obtained.

## Solution

Group terms and complete the square:

$$
\begin{aligned}
4(x^2 - 4x) + 9(y^2 + 2y) &= 11 \\
4((x - 2)^2 - 4) + 9((y + 1)^2 - 1) &= 11 \\
4(x - 2)^2 - 16 + 9(y + 1)^2 - 9 &= 11 \\
4(x - 2)^2 + 9(y + 1)^2 &= 36
\end{aligned}
$$

Divide both sides by $36$:

$$
\frac{(x - 2)^2}{9} + \frac{(y + 1)^2}{4} = 1
$$

- **Center:** $(2, -1)$.
- **Semiaxis lengths:** $a = \sqrt{9} = 3$ (horizontal) and $b = \sqrt{4} = 2$ (vertical).

Check by substituting the center $(2, -1)$ into the original left-hand side:

$$
4(2)^2 + 9(-1)^2 - 16(2) + 18(-1) - 11 = 16 + 9 - 32 - 18 - 11 = -36
$$

This is consistent with our completed-square form $4(x - 2)^2 + 9(y + 1)^2 - 36 = 0$, because at the center $(2, -1)$ both squared terms are $0$, leaving $-36$.