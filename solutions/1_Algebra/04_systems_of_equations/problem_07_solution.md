### Exercise 7. Choosing a Method Deliberately

## Question

For each situation, choose the method that best uses its structure and justify your choice:
1. One system with a triangular coefficient matrix:

$$
\begin{cases}
2x-y=3, \\
4y=8;
\end{cases}
$$

2. Three systems $Ax=b_i$ with the same invertible matrix $A$, when $A^{-1}$ is already known;
3. One $3\times3$ system for which the inverse matrix is not given and the goal is only to find one solution vector.

For case 1, carry out the chosen method completely. For cases 2 and 3, describe the plan and indicate which part of the computation would be reusable or unnecessary.

## Solution

1. **Triangular system — Back-substitution:**
Since the matrix is already triangular, no elimination is needed. Solve directly from the bottom equation up:
- From $4y = 8$, we get $y = 2$.
- Substituting into the first equation: $2x - 2 = 3 \implies 2x = 5 \implies x = \frac{5}{2}$.

The solution is $x = \frac{5}{2}$ and $y = 2$.

2. **Three systems with known $A^{-1}$ — Direct multiplication ($x_i = A^{-1}b_i$):**
Since $A^{-1}$ is already computed, we reuse it for all three right-hand sides $b_1, b_2, b_3$ by performing three quick matrix-vector multiplications. Running Gaussian elimination from scratch three separate times would be unnecessary work.

3. **One $3\times3$ system without $A^{-1}$ — Gaussian elimination on $[A \mid b]$:**
Reduce the augmented matrix $[A \mid b]$ to row echelon form and use back-substitution. Computing the full inverse $A^{-1}$ would be unnecessary extra work because we only need to solve for a single right-hand side $b$.