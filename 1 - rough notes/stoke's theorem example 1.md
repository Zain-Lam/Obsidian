2025-03-08 15:49
Status: 
Tags: [[Green's and Stokes' Theorems]]
# stoke's theorem example 1

TD: YEAR1::TERM2::MA144 Modelling 2::08 Green's and Stokes
Q: Calculate the integral $$ \iint_{S} \mathbf{F} \cdot d\mathbf{S} $$ where $\mathbf{F} = (-y, 2z, x^2)$ and $S$ is the surface $z = 4 - x^2 - y^2$ where $0 \leq z \leq 4$, using Stoke's Theorem.
A: First parametrize $C$ as $\mathbf{r}(t) = (2 \cos t, 2 \sin t, 0)$, $t \in [0, 2\pi]$ then:
$$\begin{align*} \iint_S \nabla \times \vec{F} \cdot \hat{n} \, dS &= \oint_C \mathbf{F} \cdot \frac{d\mathbf{r}}{dt} \, dt \\ \oint_{C} \mathbf{F} \cdot d\mathbf{r} &= \int_0^{2\pi} \begin{pmatrix} -2 \sin t \\ 0 \\ 4 \cos^2 t \end{pmatrix} \cdot \begin{pmatrix} -2 \sin t \\ 2 \cos t \\ 0 \end{pmatrix} \, dt \\ &= \int_0^{2\pi} 4 \sin^2 t \, dt \\ &= 4\pi \end{align*}$$
<!--ID: 1741451821700-->
