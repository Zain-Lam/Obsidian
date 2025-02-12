2025-02-12 17:12
Status: 
Tags: [[Column Vectors in Real to n]]
# line through 2 points in RR^3 

TD: YEAR1::TERM2::MA150 Algebra 2::01 Column Vectors in Real^n 
Q: What are the equations of the line $L_{PQ} \subset \mathbb{R}^3$ through the points $P = \begin{pmatrix} 2 \\ 1 \\ 3 \end{pmatrix}$ and $Q = \begin{pmatrix} 4 \\ 3 \\ 2 \end{pmatrix}$?
A: Consider a single linear equation with unknown coefficients $a, b, c, d \in \mathbb{R}$: $ax + by + cz = d$, then substitute in the components of $P$ and $Q$ into this expression to give us a system of simultaneous linear equations.
$$
\begin{align}
\text{at } P:  &\quad &2a + b + 3c &= d \\
\text{at } Q: & \quad &4a + 3b + 2c &= d
\end{align}
$$
then cancel one variable $(a)$, write another variable in terms of the other two $(b)$. Sub this into an equation to write the cancelled variable in terms of the other two.
Then you can write the linear equation in terms of just two variables.$$
\left( \frac{7}{10}c - \frac{1}{5}d \right) x + \left( \frac{8}{5}c + \frac{3}{5}d \right) y + cz = d
$$
Choose 2 pairs that aren't collinear then you have two equations that define the line $L_{PQ}$, for $c$ and $d$ the most sensible ones are $$
\begin{align}
c = 10, \, d = 0 &: \quad &7x + 16y + 10z &= 0 \\
c = 0, \, d = 5 &: \quad &x + 3y&= 5
\end{align}
$$
<!--ID: 1739381231572-->
