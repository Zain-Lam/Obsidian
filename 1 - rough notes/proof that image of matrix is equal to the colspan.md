2025-02-19 12:11
Status: 
Tags: [[Linear maps in linalg]]
# proof that image of matrix is equal to the colspan

TD: YEAR1::TERM2::MA150 Algebra 2::05 Linear Maps
Q: Prove image of $L_A$ is equal to the column span of $A$: $\operatorname{Im}(L_A) = \operatorname{Colspan}(A)$.
A: Note that $L_A(e_i) = \mathbf{c}_i$ is the $i$th column $\mathbf{c}_i$ of $A$ treated as a vector in $\mathbb{R}^m$, so we have $$ \operatorname{Colspan}(A) = \langle \mathbf{c}_1, \ldots, \mathbf{c}_n \rangle = \langle L_A(e_1), \ldots, L_A(e_n) \rangle $$ For any $\mathbf{v} \in \mathbb{R}^m$ there are unique scalars $\lambda_i \in \mathbb{R}$ so that $\mathbf{v} = \lambda_1 e_1 + \ldots + \lambda_n e_n$. Since $L_A$ is linear $$ \begin{align} L_A(\mathbf{v}) &= L_A(\lambda_1 e_1 + \ldots + \lambda_m e_n) \\ &= \lambda_1 L_A(e_1) + \ldots + \lambda_m L_A(e_n) \end{align} $$ so that $L_A(\mathbf{v})$ lies in $\operatorname{Colspan}(A)$. Thus $\operatorname{Im}(L_A) \subset \operatorname{Colspan}(A)$.
If $w \in \operatorname{Colspan}(A)$, then there are scalars $\mu_i \in \mathbb{R}$ so that $$ \begin{align} w &= \mu_1 \mathbf{c}_1 + \ldots + \mu_n \mathbf{c}_n \\ &= \mu_1 L_A(e_1) + \ldots + \mu_n L_A(e_n) \\ &= L_A(\mu_1 e_1 + \ldots + \mu_n e_n) \end{align} $$ so that $w = L_A(v)$ where $v = \mu_1 e_1 + \ldots + \mu_n e_n$ and so $w \in \operatorname{Im}(A)$. Thus $\operatorname{Colspan}(A) \subset \operatorname{Im}(A)$, and so they are equal.
<!--ID: 1739967295128-->
