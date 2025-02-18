{{date}} {{time}}
Status: 
Tags: [[Linear maps in linalg]]
# {{title}}

TD: YEAR1::TERM2::MA150 Algebra 2::05 Linear Maps 
Q: Prove that if $\varphi: V \rightarrow W$ is a linear map that is a bijection, then its set-theoretic inverse map $\varphi^{-1}: W \rightarrow V$ is also a linear map.
A: Since $\varphi$ is a bijection, there are $v_1, v_2 \in V$ so that $w_1 = \varphi(v_1)$, or equivalently $v_1 = \varphi^{-1}(w_1)$, and similarly for $w_2$. Then since we know that at least $\varphi$ is linear, we have $$\begin{align}
\varphi(\mu_1 v_1 + \mu_2 v_2) &= \mu_1 \varphi(v_1) + \mu_2 \varphi(v_2)  \\
&= \mu_1 \varphi(\varphi^{-1}(w_1)) + \mu_2 \varphi(\varphi^{-1}(w_2))  \\
&= \mu_1 w_1 + \mu_2 w_2
\end{align}$$ and now applying $\varphi^{-1}$ and subbing in inverses proves our claim.
<!--ID: 1739896426651-->
