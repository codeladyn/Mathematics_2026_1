### Exercise 1. From a System to a Matrix

## Question

Write the system

$$\begin{cases} 2x-y+z=4, \\ x+3y-2z=1, \\ 3x+y+z=7. \end{cases}$$

in the form $Ax=b$. Identify the coefficient matrix, the vector of unknowns, and the right-hand side vector. Explain how each row of the matrix corresponds to one equation.

## Solution

In matrix form $Ax = b$, the system is written as:

$$\begin{pmatrix} 2 & -1 & 1 \\ 1 & 3 & -2 \\ 3 & 1 & 1 \\ \end{pmatrix} \begin{pmatrix} x \\ y \\ z \\ \end{pmatrix} = \begin{pmatrix} 4 \\ 1 \\ 7 \\ \end{pmatrix}$$

The three parts are:

- Coefficient matrix:

$$A= \begin{pmatrix} 2 & -1 & 1 \\ 1 & 3 & -2 \\ 3 & 1 & 1 \\ \end{pmatrix}$$

- Vector of unknowns:

$$\mathbf{x}= \begin{pmatrix} x \\ y \\ z \\ \end{pmatrix}$$

- Right-hand side vector:

$$b= \begin{pmatrix} 4 \\ 1 \\ 7 \\ \end{pmatrix}$$

Each row of $A$ holds the coefficients of $x$, $y$, and $z$ from one equation in order. When you multiply a row of $A$ by the column vector of unknowns and set it equal to the matching entry in $b$, you get that exact equation back.