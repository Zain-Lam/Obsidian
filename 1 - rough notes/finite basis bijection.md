2025-02-18 15:21
Status: 
Tags: [[Vector Spaces]]
# finite basis bijection

TD: YEAR1::TERM2::MA150 Algebra 2::04 Vector spaces 
Q: Let $V$ be a vector space and $\mathcal{B} = \{v_1, \ldots, v_n\}$ a basis. Then for the bijection $$ \chi_{\mathcal{B}} : V \rightarrow \mathbb{R}^n $$what can be said about an individual element?
A: $$ v \mapsto \begin{pmatrix} \lambda_1 \\ \vdots \\ \lambda_n \end{pmatrix} $$ where $v = \lambda_1 v_1 + \ldots + \lambda_n v_n$, which respects the vector space operations: that is, $$ \chi_{\mathcal{B}}(v) + \chi_{\mathcal{B}}(w) = \chi_{\mathcal{B}}(v + w) \quad \text{and} \quad \chi_{\mathcal{B}}(\lambda v) = \lambda \chi_{\mathcal{B}}(v) $$ for all $v, w \in V$ and $\lambda \in \mathbb{R}$.
<!--ID: 1739892200012-->
