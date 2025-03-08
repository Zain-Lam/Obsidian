2025-03-08 13:26
Status: 
Tags: [[Green's and Stokes' Theorems]]
# Green's Theorem example 3

TD: YEAR1::TERM2::MA144 Modelling 2::08 Green's and Stokes
Q: Evaluate $I = \oint_{C} (y^2 \, dx + xy \, dy)$ where $C$ is the triangle $OAB$ with vertices at $O(0, 0)$, $A(1, 0)$, $B(1, 2)$, do this using Green's Theorem.
A: Using Green's$$\begin{align}
I &= \iint_D (y - 2y) \, dx \, dy \\
&= - \int_0^2 \int_{y/2}^1 y \, dx \, dy  \\
&= - \int_0^2 y \left(1 - \frac{y}{2}\right) \, dy  \\
&= \left[ \frac{y^3}{6} - \frac{y^2}{2} \right]_0^2 = \frac{4}{3} - 2 = -\frac{2}{3}
\end{align}$$
<!--ID: 1741440696627-->
