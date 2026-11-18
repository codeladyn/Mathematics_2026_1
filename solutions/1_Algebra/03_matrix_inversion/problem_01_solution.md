### Exercise 1. Definition of the Inverse

## Question

For the matrices:

$$A= \begin{pmatrix} 2 & 1 \\ 1 & 1 \\ \end{pmatrix},\qquad B= \begin{pmatrix} 1 & -1 \\ -1 & 2 \\ \end{pmatrix}$$

Check, without using a formula, whether $B=A^{-1}$. Compute $AB$ and $BA$ and relate the result to the definition of the inverse.

## Solution

First, compute the product $AB$:

$$\begin{aligned} AB &= \begin{pmatrix} 2 & 1 \\ 1 & 1 \\ \end{pmatrix} \begin{pmatrix} 1 & -1 \\ -1 & 2 \\ \end{pmatrix} \\ &= \begin{pmatrix} 2(1)+1(-1) & 2(-1)+1(2) \\ 1(1)+1(-1) & 1(-1)+1(2) \\ \end{pmatrix} \\ &= \begin{pmatrix} 1 & 0 \\ 0 & 1 \\ \end{pmatrix} \end{aligned}$$

Next, compute the product $BA$:

$$\begin{aligned} BA &= \begin{pmatrix} 1 & -1 \\ -1 & 2 \\ \end{pmatrix} \begin{pmatrix} 2 & 1 \\ 1 & 1 \\ \end{pmatrix} \\ &= \begin{pmatrix} 1(2)+(-1)(1) & 1(1)+(-1)(1) \\ (-1)(2)+2(1) & (-1)(1)+2(1) \\ \end{pmatrix} \\ &= \begin{pmatrix} 1 & 0 \\ 0 & 1 \\ \end{pmatrix} \end{aligned}$$

By definition, a matrix $B$ is the inverse of $A$ ($B = A^{-1}$) if and only if multiplying them in either order gives the identity matrix $I$. Since $AB = I$ and $BA = I$, $B$ is indeed $A^{-1}$.