2025-02-18 13:11
Status: 
Tags: [[Vector Spaces]]
# exchange lemma for bases

TD: YEAR1::TERM2::MA150 Algebra 2::04 Vector spaces 
Q: Let $V$ be a vector space and $\mathcal{B} = \{v_1, \ldots, v_s\}$ be a basis of $V$. Suppose $w \in V$ with $w \neq 0_V$. How can we find a new basis?
A: Since $\mathcal{B}$ is a basis, there are (unique) scalars $\lambda_i \in \mathbb{R}$ so that $$ w = \lambda_1 v_1 + \ldots + \lambda_s v_s $$If $\lambda_j \neq 0$, then $$ \{v_1, \ldots, v_{j-1}, v_{j+1}, \ldots, v_s\} \cup \{w\} $$is also a basis of $V$, where the element $v_j$ has been removed from the first factor of the union.
<!--ID: 1739884387249-->
