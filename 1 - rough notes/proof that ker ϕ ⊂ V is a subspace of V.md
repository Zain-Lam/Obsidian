2025-02-18 16:20
Status: 
Tags: [[Linear maps in linalg]]
# proof that ker ϕ ⊂ V is a subspace of V

TD: YEAR1::TERM2::MA150 Algebra 2::05 Linear Maps 
Q: Given a linear map $\varphi: V \rightarrow W$, prove that $\ker \varphi \subset V$ is a subspace of $V$.
A: We know $0_V \in \ker \varphi$. Suppose $v_1, v_2 \in \ker \varphi$ and $\lambda_1, \lambda_2 \in \mathbb{R}$. Then by linearity of $\varphi$ $$ \varphi(\lambda_1 v_1 + \lambda_2 v_2) = \lambda_1 \varphi(v_1) + \lambda_2 \varphi(v_2) = \lambda_1 0_V + \lambda_2 0_V = 0_V $$and so $\lambda_1 v_1 + \lambda_2 v_2 \in \ker \varphi$, as required.
<!--ID: 1739895771012-->
