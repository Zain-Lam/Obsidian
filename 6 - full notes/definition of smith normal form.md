2025-02-15 21:57
Status: 
Tags: [[Subspaces and Bases of RRn]]
# definition of smith normal form

TD: YEAR1::TERM2::MA150 Algebra 2::03 Subspaces and Bases of R^n 
Q: When is a matrix in smith normal form?
A: A matrix $A \in \operatorname{Mat}_{m \times n}$ is in Smith normal form if and only if it is in the form $$ A = \begin{pmatrix} I_r & 0_{r, n-r} \\ 0_{m-r, r} & 0_{m-r, n-r} \end{pmatrix} = \left(
\begin{array}{ccccc|ccc}
1 & 0 & 0 & \cdots & 0 & 0 & \cdots & 0 \\ 
0 & 1 & 0 & \cdots & 0 & 0 & \cdots & 0 \\ 
\vdots & \vdots & \vdots & \ddots & \vdots & \vdots & \ddots & \vdots \\ 
0 & 0 & 0 & \cdots & 1 & 0 & \cdots & 0 \\ 
\hline 
0 & 0 & 0 & \cdots & 0 & 0 & \cdots & 0 \\ 
\vdots & \vdots & \vdots & \ddots & \vdots & \vdots & \ddots & \vdots \\ 
0 & 0 & 0 & \cdots & 0 & 0 & \cdots & 0 
\end{array}
\right) $$The rank of this Smith normal form is defined to be the integer $r \geq 0$.
<!--ID: 1739657163013-->
