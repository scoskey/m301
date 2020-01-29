---
title: Math 301, Spring 2020
---

# Math 301 Homework

## Homework 3, due Thursday, February 6 at 12pm

1. Factor the following matrices into $LU$ form.
  * $\begin{bmatrix}2&-3\\\\1&-3\end{bmatrix}$
  * $\begin{bmatrix}1&0&1\\\\2&2&2\\\\3&4&5\end{bmatrix}$
2. Use your decomposition from the previous problem to solve each system. (Do not use elimination again! Instead rewrite each system as two triangular systems and use forth-solving and back-solving.)
  * $\set{x+z=4,\ 2x+2y+2z=4,\ 3x+4y+5z=6}$
  * $\set{x+z=2,\ 2x+2y+2z=6,\ 3x+4y+5z=14}$
3. Factor the *tridiagonal* matrix $A$ into $A = LU$. Do you observe anything special about the solution?
  $A=\begin{bmatrix}2 & 1 & 0 \\\\ 1 & 2 & 1 \\\\ 0 & 1 & 2\end{bmatrix}$
4. Consider a matrix $A$ which is already lower triangular:
  $A=\begin{bmatrix}1&0&0\\\\a&1&0\\\\b&c&1\end{bmatrix}$
  * What are the elimination matrices $E\_1$, $E\_2$, $E\_3$ that reduce $A$ to upper triangular form?
  * What is the product of the elimination matrices $E=E\_3E\_2E\_1$?
  * What are $L$ and $U$ in this case?
5. ... tba

## Homework 2, due Thursday, January 30 at 12pm

1. Let $A$ be the matrix below. Find $A^2$ and $A^3$. What will $A^{100}$ be?  
  $\begin{bmatrix}1&0&0\\\\0&1&0\\\\0&a&1\end{bmatrix}$
2. Consider the matrices $A$ and $B$ below. Compute both $A^2+2AB+B^2$ and $(A+B)^2$. Are they the same? If not, what is the correct rule?  
   $A=\begin{bmatrix}1&2\\\\0&0\end{bmatrix},\qquad
    B=\begin{bmatrix}1&0\\\\3&0\end{bmatrix}$
3. Decide whether the following statements are true or false. If true, explain why, and if false give an example showing that it is false.
  * $A^2$ only makes sense if $A$ is a square matrix
  * If $AB$ and $BA$ both make sense, then $A$ and $B$ are square matrices.
  * If $AB$ and $BA$ both make sense, then $AB$ and $BA$ are square matrices.
  * If $AB=B$ then $A$ is the identity matrix.
4. For each system of equations, write the corresponding augmented matrix and use elimination to solve it.  In each step, keep note of the elimination matrices you used.
  * $\set{-3x+4y=-11;\ 3x+5y=20}$
  * $\set{-x-2y+z=-4;\ 2x+4y+3z=3; 3y+2z=1}$
5. What $3\times3$ matrix $E$ multiplies a vector $(x,y,z)$ to give $(x,y+z,2y)$? (Note: I type my vectors horizontally to save vertical space on the page only. The question will be easier if you write them vertically.)
6. Apply elimination to the augmented matrix. For what value of $c$ does the system have a solution?  
  $\begin{bmatrix}1 & 2 & 3 &\vert &1 \\\\ 2 & 3 & 4 & \vert & 2 \\\\ 4 & 7 & 10 & \vert & c\end{bmatrix}$
7. Write down the row operations corresponding to the elimination matrices:
  * $\begin{bmatrix}1 & 0 & 0\\\\ 3 & 1 & 0\\\\ 0 & 0 & 1\end{bmatrix}$
  * $\begin{bmatrix}1 & 2 & 0\\\\ 0 & 1 & 0\\\\ 0 & 0 & 1\end{bmatrix}$
  * $\begin{bmatrix}1 & 0 & 0\\\\ 0 & 0 & 1\\\\ 0 & 1 & 0\end{bmatrix}$
8. Write down the elimination matrix that *undoes* the affect of the given elimination matrix.
  * $\begin{bmatrix}1&0&0\\\\0&1&0\\\\3&0&1\end{bmatrix}$
  * $\begin{bmatrix}1&0&0\\\\-3&1&0\\\\4&0&1\end{bmatrix}$ (this is a double elimination matrix which performs two operations)

## Homework 1, due Thursday, January 23 at 12pm

1. Solve the system of linear equations using any method.
   * $\set{2x+y+z=2;\ x+2y+3z=1;\ y+2z=0}$
2. For each of the following systems, carefully graph the equations and the location of the solution. Then graph the "vector picture" (the right-hand side as the tip of a parallelogram made from two column vectors). Finally, find the solution.
  * $\set{x-2y=0;\ x+y=6}$
  * $\set{2x+3y=1;\ 10x+9y=11}$
3. Consider a system with two equations and three variables $x,y,z$, fill in the blanks. Explain your reasoning with one complete sentence for each answer.
  * The ordinary graph of the system will show (2 / 3) (lines / planes) in (2 / 3)-dimensional space.
  * The vector picture will show (2 / 3 / 4) vectors in (2 / 3)-dimensional space.
4. The intersection of the two planes defined by $x+y+3z=6$ and $x-y+z=4$ is a line. Find the point on this line with $z=0$, and the point on this line with $z=2$. Find another point on this line.
5. Suppose you have three planes, $P_1$, $P_2$, and $P_3$. Suppose you know that there are at least two points in the intesection of the three planes. Explain why you can conclude there are actually infinitely many points in the intersection of the three planes.

<!-- % 2.1, exercises 4, 5, 6, 26, and 28. -->

<script>
window.MathJax = {
  tex: {
    inlineMath: [['$','$'], ['\\(','\\)']],
    processEscapes: true,
    macros: {
      set: ["{\\left\\{ #1 \\right\\}}", 1],
      abs: ["{\\left| #1 \\right|}", 1],
      lt: ["<"]
    }
  }
};
</script>

<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>