### Exercise 3. When Can Matrices Be Multiplied?

## Question

The matrix sizes are given as:

$$
A_{2\times3},\qquad B_{3\times4},\qquad C_{4\times2},\qquad D_{2\times2}
$$

For the products $AB, BA, BC, CB, AC, CA, AD, DA$, determine whether they are defined. If so, state the size of the result. Justify each decision using the dimension compatibility condition.

## Solution

- $AB$: Defined. Dimensions $2 \times 3$ and $3 \times 4$ match ($3=3$). Result is $2 \times 4$.
- $BA$: Undefined. Dimensions $3 \times 4$ and $2 \times 3$ do not match ($4 \neq 2$).
- $BC$: Defined. Dimensions $3 \times 4$ and $4 \times 2$ match ($4=4$). Result is $3 \times 2$.
- $CB$: Undefined. Dimensions $4 \times 2$ and $3 \times 4$ do not match ($2 \neq 3$).
- $AC$: Undefined. Dimensions $2 \times 3$ and $4 \times 2$ do not match ($3 \neq 4$).
- $CA$: Defined. Dimensions $4 \times 2$ and $2 \times 3$ match ($2=2$). Result is $4 \times 3$.
- $AD$: Undefined. Dimensions $2 \times 3$ and $2 \times 2$ do not match ($3 \neq 2$).
- $DA$: Defined. Dimensions $2 \times 2$ and $2 \times 3$ match ($2=2$). Result is $2 \times 3$.

You can only multiply matrices if the "inside" numbers match. For example, a $2 \times 3$ and a $3 \times 4$ work because the $3$s match. The size of the new matrix you get is just the "outside" numbers (so, $2 \times 4$).