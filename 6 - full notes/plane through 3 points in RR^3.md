2025-02-12 17:01
Status: 
Tags: [[Column Vectors in Real to n]]
# plane through 3 points in RR^3 

TD: YEAR1::TERM2::MA150 Algebra 2::01 Column Vectors in Real^n 
Q: Find the plane $\Pi_{PQR} \subset \mathbb{R}^3$ through $P = \begin{pmatrix} 1 \\ 1 \\ 1 \end{pmatrix}$, $Q = \begin{pmatrix} 1 \\ 2 \\ 1 \end{pmatrix}$, and $R = \begin{pmatrix} 0 \\ 2 \\ 3 \end{pmatrix}$.
A: Its equation is of the form $ax + by + cz = d$ for $a, b, c, d \in \mathbb{R}$ with $(a, b, c) \neq (0, 0, 0)$. So we can turn this into a set of simultaneous linear equations.$$
\begin{align}
\text{at } P: & \quad &a + b + c &= d \\
\text{at } Q: & \quad &a - b + 2c &= d \\
\text{at } R: & \quad &\phantom{a} \, 2b + 3c &= d
\end{align}
$$If we choose a particular solution (one deg of freedom) then we can find the nontrivial solution $(a, b, c, d) = (5, 1, 2, 8)$ which gives us $$\Pi_{PQR}: (5x + y + 2z = 8) \subset \mathbb{R}^3$$Which we check that points satisfy this solution.
<!--ID: 1739380217458-->
