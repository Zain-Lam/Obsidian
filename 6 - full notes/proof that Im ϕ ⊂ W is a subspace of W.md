2025-02-18 16:23
Status: 
Tags: [[Linear maps in linalg]]
# proof that Im ϕ ⊂ W is a subspace of W

TD: YEAR1::TERM2::MA150 Algebra 2::05 Linear Maps 
Q: Given a linear map $\varphi: V \rightarrow W$, prove that $\operatorname{Im} \varphi \subset W$ is a subspace of $W$.
A: We know $0_W \in \operatorname{Im} \varphi$. Suppose $w_1, w_2 \in \operatorname{Im} \varphi$ and $\mu_1, \mu_2 \in \mathbb{R}$. Then by the definition of the image, there exist $v_1, v_2 \in V$ with $w_1 = \varphi(v_1)$ and $w_2 = \varphi(v_2)$. So by linearity of $\varphi$ $$ \mu_1 w_1 + \mu_2 w_2 = \mu_1 \varphi(v_1) + \mu_2 \varphi(v_2) = \varphi(\mu_1 v_1 + \mu_2 v_2) $$is also in $\operatorname{Im} \varphi$, as required.
<!--ID: 1739896426657-->
