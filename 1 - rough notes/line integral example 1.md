2025-02-25 22:23
Status: 
Tags: [[Green's and Stokes' Theorems]]
# line integral example 1

TD: YEAR1::TERM2::MA144 Modelling 2::08 Green's and Stokes
Q: Find the work done by $\mathbf{F} = (2y^2, z^2, x^2)$ on a particle along the line segment from $(0,0,1)$ to $(2,1,0)$.
A: First we parametrise the curve to get:
$$
\underline{\mathbf{r}}(t)=\begin{pmatrix}
0 \\
0 \\
1
\end{pmatrix} + t \begin{pmatrix}
2 \\
1 \\
-1
\end{pmatrix}
\quad t\in[0,1]
$$and we can see that $$
\begin{align}
x&=2t \\
y&=t \\
z&=1-t
\end{align}
$$so the line integral is $$
\int\limits_{0}^{1}\begin{pmatrix}
2t^{2} \\
(1-t)^{2} \\
4t^{2}
\end{pmatrix}\cdot
\begin{pmatrix}
2 \\
1 \\
-1
\end{pmatrix}=\frac{1}{3}
$$source: trust me bro
<!--ID: 1740522568013-->
