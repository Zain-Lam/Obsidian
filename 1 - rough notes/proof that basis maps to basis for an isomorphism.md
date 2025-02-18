2025-02-18 16:42
Status: 
Tags: [[Vector Spaces]]
# proof that basis maps to basis for an isomorphism

TD: YEAR1::TERM2::MA150 Algebra 2::04 Vector spaces 
Q: Prove that if $\varphi: V \rightarrow W$ is an isomorphism then if $\mathcal{B} \subset V$ is a basis of $V$, then $\varphi(\mathcal{B}) = \{\varphi(v) \mid v \in \mathcal{B}\}$ is a basis of $W$.
A: We first show that $\varphi(\mathcal{B})$ spans. Let $w \in W$. Consider $v = \varphi^{-1}(w) \in V$. Since $\mathcal{B}$ is a basis of $V$, there are elements $v_1, \ldots, v_s \in \mathcal{B}$ and scalars $\lambda_1, \ldots, \lambda_s \in \mathbb{R}$ so that $$v = \lambda_1 v_1 + \ldots + \lambda_s v_s$$Applying $\varphi$ to both sides we have $$\begin{align} w = \varphi(v) &= \varphi(\lambda_1 v_1 + \ldots + \lambda_s v_s) \\ &= \lambda_1 \varphi(v_1) + \ldots + \lambda_s \varphi(v_s) \end{align}$$which does indeed express $w$ as a linear combination of elements of $\varphi(\mathcal{B})$.
To finish, we show that $\varphi(\mathcal{B})$ is linearly independent.
Suppose $$0_W = \lambda_1 \varphi(v_1) + \ldots + \lambda_s \varphi(v_s)$$for elements $\varphi(v_i) \in \varphi(\mathcal{B})$ and scalars $\lambda_i \in \mathbb{R}$. We must show that all $\lambda_i = 0$. So applying $\varphi^{-1}$ to both sides we have $$\begin{align} 0_V &= \varphi^{-1}(0_W) = \varphi^{-1}(\lambda_1 \varphi(v_1) + \ldots + \lambda_s \varphi(v_s)) \\ &= \lambda_1 \varphi^{-1}(\varphi(v_1)) + \ldots + \lambda_s \varphi^{-1}(\varphi(v_s)) \\ &= \lambda_1 v_1 + \ldots + \lambda_s v_s \end{align}$$But $v_1, \ldots, v_s \in \mathcal{B}$, and $\mathcal{B}$ is linearly independent, so we conclude at once that $\lambda_1 = \ldots = \lambda_s = 0$, which is what we were required to do. Game over.