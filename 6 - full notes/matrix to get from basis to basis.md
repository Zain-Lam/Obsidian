2025-02-19 13:30
Status: 
Tags: [[Linear maps in linalg]]
# matrix to get from basis to basis

TD: YEAR1::TERM2::MA150 Algebra 2::05 Linear Maps
Q: Let $V$ be a vector space with basis $v_1, \ldots, v_n$ and $W$ be a vector space with basis $w_1, \ldots, w_m$, how do we find a matrix for the linear map that goes from one to the other.
A: If $A = (a_{ij}) \in \operatorname{Mat}_{m \times n}$ is a matrix, then there is a linear map $\varphi_A$ defined on the basis of $V$ by $$ \begin{align}
\varphi_A : V &\rightarrow W \\
v_i &\mapsto a_{1i}w_1 + \ldots + a_{mi}w_m 
\end{align}$$where the coefficients of $\varphi_A(v_i)$ with respect to the basis of $W$ are the $i$th column of $A$.
<!--ID: 1739974134021-->
