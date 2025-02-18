2025-02-18 16:16
Status: 
Tags: [[Linear maps in linalg]]
# proof for when a linear map is injective

TD: YEAR1::TERM2::MA150 Algebra 2::05 Linear Maps 
Q: Given a linear map $\varphi: V \rightarrow W$, prove that $\varphi$ is injective if and only if $\ker \varphi = \{0_V\}$.
A: Suppose that $\ker \varphi = \{0_V\}$ and we have $v_1, v_2 \in V$ with $\varphi(v_1) = \varphi(v_2)$. We must prove that $v_1 = v_2$. By linearity of $\varphi$, $$ \varphi(v_1 - v_2) = \varphi(v_1) + \varphi((-1)v_2) = \varphi(v_1) - \varphi(v_2) = 0_W $$so that $v_1 - v_2 \in \ker \varphi$. Therefore $v_1 - v_2 = 0_V$, or in other words $v_1 = v_2$, as required.
The converse is quicker: if $\varphi$ is injective, then at most one element may map to $0_W$, and since $\varphi(0_V) = 0_W$, we have $\ker \varphi = \{0_V\}$.
<!--ID: 1739895518125-->
