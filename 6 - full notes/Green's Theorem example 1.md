2025-03-08 12:47
Status: 
Tags: [[Green's and Stokes' Theorems]]
# Green's Theorem example 1

TD: YEAR1::TERM2::MA144 Modelling 2::08 Green's and Stokes
Q: Let $C$ be the ellipse $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$. Use Green’s Theorem to calculate the area of the ellipse.
A: Choose $P, Q$ in Green's Theorem such that $Q_x - P_y = 1$.
Example: $Q = x, P = 0$.
LHS = $\iint_D dx \, dy =$ area of ellipse.
RHS = $\oint_C x \frac{dy}{dt} \, dt$.
Parametrising: $$\begin{align*} C: \, \mathbf{r}(t) &= (a \cos t, b \sin t), \, t \in [0, 2\pi] \\ RHS&= \int_0^{2\pi} a \cos t (b \cos t) \, dt \\ &= ab \int_0^{2\pi} \cos^2 t \, dt \\ &= \pi ab \end{align*}$$
<!--ID: 1741439563240-->

