---
title: Math 301, Spring 2020
---

# Math 301 Homework

## Homework 7, due Thursday, March 12 at 12pm

1. In each problem, let $V$ be the subspace with the given basis. Find a basis for $V^\perp$.
  * Basis for $V$: $\begin{bmatrix}1\\\\3\\\\4\end{bmatrix},\quad
     \begin{bmatrix}5\\\\2\\\\7\end{bmatrix}$
  * Basis for $V$: $\begin{bmatrix}1\\\\2\\\\2\\\\3\end{bmatrix},\quad
     \begin{bmatrix}1\\\\3\\\\3\\\\2\end{bmatrix}$
2. Let $A$ be the given matrix. Draw the (traditional) graph of $R(A)$ and $N(A)$ on one set of axes, and the graph of $C(A)$ and $LN(A)$ on a second set of axes.  
   $A=\begin{bmatrix}1&2\\\\3&6\end{bmatrix}$
3. Can you construct a $2\times 2$ matrix $A$ such that the sum of the rows of $A$ is the vector $(1,1)$ and the sum of the columns of $A$ is the vector $(0,0)$? If not, why not?
4. Find the projection of $\mathbf{b}$ onto the line through $\mathbf{a}$.
  * $\mathbf b=(2,-1,0)$, $\mathbf a=(1,0,1)$
  * $\mathbf b=(1,2,2)$, $\mathbf a=(1,1,1)$
5. Let $A\mathbf{x}=\mathbf{b}$ be the inconsistent system below. Find the best approximate solution $\hat{\mathbf{x}}$ and the projection $\mathbf{p}$ of $\mathbf{b}$ to $C(A)$.
  * $\begin{bmatrix}1&1\\\\2&0\\\\-1&1\end{bmatrix}\mathbf{x}
  =\begin{bmatrix}2\\\\1\\\\1\end{bmatrix}$
  * $\begin{bmatrix}1&0\\\\2&1\\\\0&1\end{bmatrix}\mathbf{x}
  =\begin{bmatrix}5\\\\0\\\\0\end{bmatrix}$
6. For the matrix $A$ in exercise 5(a), find the projection matrix $P$.
7. When projecting $\mathbf{b}$ onto the column space of a matrix $A$, which of the four subspaces contains the projection $\mathbf{p}$? Which of the four subspaces contains the error vector $\mathbf{b}-\mathbf{p}$? Explain your answers.

<!-- Can you construct a $2\times 2$ matrix $A$ such that the sum of the rows of $A$ is the vector $(1,1)$ and the sum of the columns of $A$ is the vector $(0,0)$? If not, why not? -->

## Homework 6, due Thursday, March 5 at 12pm

1. For each matrix $A$, find bases for all four fundamental subspaces. <!--For each space state it is a \_\_\_-dimensional subspace of $\mathbb{R}$^\_\_\_.-->
  * $A=\begin{bmatrix}1&-1&3\\\\-2&2&-6\end{bmatrix}$
  * $A=\begin{bmatrix}1&2&4\\\\0&1&-2\end{bmatrix}$
  * $A=\begin{bmatrix}1&3&0&-1\\\\2&6&1&-4\\\\1&3&-2&3\end{bmatrix}$
  * $A=\begin{bmatrix}2&0&-1&4&2\\\\4&1&0&2&-1\\\\2&1&1&-2&-3\end{bmatrix}$
2. What is the dimension of the subspace spanned by the following set? Eliminate redundant vectors from the list to reduce it to an independent set.  
  $\begin{bmatrix}1\\\\-1\\\\0\\\\0\end{bmatrix},\quad
  \begin{bmatrix}1\\\\0\\\\-1\\\\0\end{bmatrix},\quad
  \begin{bmatrix}1\\\\0\\\\0\\\\-1\end{bmatrix},\quad
  \begin{bmatrix}0\\\\1\\\\-1\\\\0\end{bmatrix},\quad
  \begin{bmatrix}0\\\\1\\\\0\\\\-1\end{bmatrix},\quad
  \begin{bmatrix}0\\\\0\\\\1\\\\-1\end{bmatrix}$
3. Find bases for the column space and row space of each matrix. Which two of these four subspaces are identical?  
  $\begin{bmatrix}1&1&0\\\\1&3&1\\\\3&1&-1\end{bmatrix},\quad
  \begin{bmatrix}1&1&0\\\\0&2&1\\\\0&0&0\end{bmatrix}$
4. Suppose you are given a set of four vectors in $\mathbb R^3$. Your friend tells you the set cannot possibly be independent. Is this true or false, and explain why.
5. Suppose that $A$ is a $10\times10$ matrix and that its column space is contained in its null space. Explain how you know that $A$ must have $\leq5$ pivots.
6. Suppose $EA=R$, with $E$ and $R$ given below. Find bases for the row space, null space, and left-null space of $A$. (Do not calculate $A$.)  
  $E=\begin{bmatrix}1&0&0\\\\6&1&0\\\\9&8&1\end{bmatrix},\qquad
    R=\begin{bmatrix}1&0&0&4\\\\0&1&0&3\\\\0&0&1&2\end{bmatrix}$
    <!--make less boring / also think about the E method-->
7. If $A$ is a matrix that is wider than it is tall, then $A$ has a nonzero \_\_\_\_\_ space. If $A$ is a matrix that is taller than it is wide, then $A$ has a nonzero \_\_\_\_\_ space. Explain your reasoning!

## Homework 5, due Thursday, February 27 at 12pm

1. Eliminate to RREF.
  * $\begin{bmatrix}-1&3&5\\\\-2&6&10\end{bmatrix}$
  * $\begin{bmatrix}-1&3&5\\\\-2&6&7\end{bmatrix}$
2. For each of the following matrices $A$, if it has a nonzero null space, find its null space matrix $N$ (the matrix whose columns are the special solutions). Check that $AN=0$.
  * $A=\begin{bmatrix}2&3\\\\4&6\\\\-2&-3\end{bmatrix}$
  * $A=\begin{bmatrix}2&3\\\\4&6\\\\-2&-6\end{bmatrix}$
3. Give an example of a matrix whose column space contains the vectors $(1,1,5)$ and $(0,3,1)$ and whose null space contains the vector $(1,1,2)$.
4. Going back and forth between systems and parametric forms.
  * Solve the ``system'' of equations $x - 3y - z = 0$. Write your answer in parametric vector form.
  * Find the column space of the matrix $N=\begin{bmatrix}3&1\\\\1&0\\\\0&1\end{bmatrix}$
5. For each system, solve or state that it is inconsistent. If the system is consistent, find the null space in parametric vector form, the particular solution, and finally write the general solution.
  * $\\{2y+z=1,\ x-4y-2z=1,\ x=1\\}$
  * $\\{2y+z=1,\ x-4y-2z=2,\ x=4\\}$
  * $\begin{bmatrix}1&0&2&3\\\\1&3&2&0\\\\2&0&4&9\end{bmatrix}\mathbf{x}
    =\begin{bmatrix}2\\\\5\\\\10\end{bmatrix}$
6. Give an example of a system of two equations in three variables with particular solution $\mathbf x_p=(2,4,0)$ and with special solution $(1,1,1)$.

## Homework 4, due Thursday, February 13 at 12pm

1. Find the column space of each matrix $A$. The answer consists of one or more equations in the variables $b\_1,b\_2,b\_3$ that decide when $A\mathbf{x}=\mathbf{b}$ has a solution.
  * $A=\begin{bmatrix}2&1&1\\\\4&2&1\\\\-2&-1&0\end{bmatrix}$
  * $A=\begin{bmatrix}2&1&1\\\\4&2&2\\\\-2&-1&-1\end{bmatrix}$
2. For each matrix below, what is the geometric shape of the column space? Your answer should say whether it is a (point / line / plane / etc) in $\mathbb R$ to the (1 / 2 / 3 / etc). Briefly explain your answers!  
  $\begin{bmatrix}1&2\\\\0&0\\\\0&0\end{bmatrix},\quad
  \begin{bmatrix}1&0\\\\0&2\\\\0&0\end{bmatrix},\quad
  \begin{bmatrix}1&0\\\\2&0\\\\0&0\end{bmatrix}$
3. Suppose $A$ is a matrix and $B$ is the same matrix $A$ except with an additional column added onto the right. Can the column space of $B$ be larger than the column space of $A$? Can the column space of $B$ be the same as the column space of $A$? For each question give an example or say why it is not possible to do so.
4. Suppose that $A$ is a $5\times5$ invertible matrix. What is the column space of $A$? How do you know?

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
5. Find the inverse of each matrix, or show that it is singular.
  * $\begin{bmatrix}e&2e\\\\3e&4e\end{bmatrix}$
  * $\begin{bmatrix}1&3\\\\2&7\end{bmatrix}$
  * $\begin{bmatrix}1&-1&1\\\\1&1&1\\\\1&2&4\end{bmatrix}$
6. If $A=\begin{bmatrix}1&1\\\\1&1\end{bmatrix}$ find two matrices $B,C$ such that $AB=AC$ but $B\neq C$. If $A$ is invertible, explain why this would be impossible.
7. Find invertible matrices $A$ and $B$ such that $A+B$ is singular. Find singular matrices $A$ and $B$ such that $A+B$ is invertible.
8. Find three values of $c$ that make the following matrix singular. Explain why it is singular in each case.  
  $A=\begin{bmatrix}2&c&c\\\\c&c&c\\\\8&7&c\end{bmatrix}$
9. Use elimination to reduce the following matrix to upper triangular form. In your work you may assume that $a\neq 0$ and $a\neq b$. Considering the three pivots, explain why the matrix is invertible.  
  $A=\begin{bmatrix}a&b&b\\\\a&a&b\\\\a&a&a\end{bmatrix}$

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
6. Apply elimination to the augmented matrix. For what value of $c$ does the system have solutions?  
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

## Homework specifications

Please write neatly and show all work in a clear flow. If you submit by hand, please tear off ragged edges from spiral notebooks. If you submit by email, please use a high quality scanner or app to ensure the following: all pages are included in a single pdf attachment, only the paper is visible, the background is white, the text is dark and legible, and your name appears on the first page.

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