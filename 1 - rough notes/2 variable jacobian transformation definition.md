2025-02-25 20:59
Status: 
Tags: [[Calculus of multivariable functions]]
# 2 variable jacobian transformation definition

TD: YEAR1::TERM2::MA144 Modelling 2::07 Calculus of multivariable functions.
Q: Let $F : R \subseteq \mathbb{R}^2 \to \mathbb{R}^2$ be defined by $F(u, v) = (x, y)$ be a bijection which represents a coordinate transformation $x = x(u, v)$ and $y = y(u, v)$. Then how do you express the integral of $f : R \subseteq \mathbb{R}^2 \to \mathbb{R}$ in terms of $u,v$
A: We can write $$ \iint_{R} f(x, y) \, dx \, dy = \iint_{S} f(u, v) \left| \det \underline{DF}(u, v) \right| \, du \, dv $$where $S = F^{-1}(R)$ is the corresponding region in the $(u, v)$ plane.
And the matrix $\underline{DF}(u,v)$ called the Jacobian Matrix is defined by $$
\underline{DF}(u,v)=\begin{pmatrix}
x_{u} & x_{v} \\
y_{u} & y_{v}
\end{pmatrix}
$$
<!--ID: 1740517364189-->

