2025-02-15 21:03
Status: 
Tags: [[Subspaces and Bases of RRn]]
# changing the basis of a vector

TD: YEAR1::TERM2::MA150 Algebra 2::03 Subspaces and Bases of R^n 
Q: Given two bases $f$ and $g$ and a vector $\underline{\mathbf{w}}$ in terms of $f$, how do we write it in terms of $g$
A: Suppose $f_{i}$ has scalar coefficient $a_{i}$ then $\underline{\mathbf{w}}$ can be written as the matrix $$
\begin{pmatrix}
\underline{f}_{1} & \underline{f}_{2}&\dots&\underline{f}_{n}
\end{pmatrix}
\begin{pmatrix}
a_{1} \\
\vdots \\
a_{n}
\end{pmatrix}
=Q_{f}\begin{pmatrix}
a_{1} \\
\vdots \\
a_{n}
\end{pmatrix}
$$
Since $g$ is also a basis, the vector $\underline{\mathbf{w}}$ can be found with coefficients $b_{i}$ as it can be written as $Q_{g}\begin{pmatrix}b_{1} \\\vdots \\b_{n}\end{pmatrix}$ it follows that, $$
\begin{pmatrix}
b_{1} \\
\vdots \\
b_{n}
\end{pmatrix}
=Q_{g}^{-1}
Q_{f}\begin{pmatrix}
a_{1} \\
\vdots \\
a_{n}
\end{pmatrix}
$$Being careful of the order.
<!--ID: 1739654001482-->
