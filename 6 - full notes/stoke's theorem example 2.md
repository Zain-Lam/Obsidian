2025-03-08 16:08
Status: 
Tags: [[Green's and Stokes' Theorems]]
# stoke's theorem example 2

TD: YEAR1::TERM2::MA144 Modelling 2::08 Green's and Stokes
Q: Calculate the integral $$ \iint_{S} \mathbf{F} \cdot d\mathbf{S} $$ where $\mathbf{F} = (-y, 2z, x^2)$ and $S$ is the surface $z = 4 - x^2 - y^2$ where $0 \leq z \leq 4$, using the net circulation on a simpler surface with the same rim
A: b) Try evaluating the net circulation on the disc radius 2. $$ \nabla \times \mathbf{F} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ \partial/\partial x & \partial/\partial y & \partial/\partial z \\ -y & 2z & x^2 \end{vmatrix} = (-2, -2x, 1)$$and the normal is $\hat{n} = (0, 0, 1)$ for the disc$$\begin{align}
\iint_S \nabla \times \mathbf{F} \cdot \hat{n} \, dS &= \iint_S \, dS \quad \text{(area of the disc, radius 2)} \\
&= 4\pi
\end{align}$$
<!--ID: 1741451821695-->
