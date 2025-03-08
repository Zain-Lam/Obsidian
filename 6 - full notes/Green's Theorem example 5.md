2025-03-08 13:41
Status: 
Tags: [[Green's and Stokes' Theorems]]
# Green's Theorem example 5

TD: YEAR1::TERM2::MA144 Modelling 2::08 Green's and Stokes
Q: Use Green’s Theorem to show that in polar coordinates, $$ dA = r \, dr \, d\theta. $$.
A: Using Green's $$
\begin{align*} &= \iint_R \, dx \, dy \\ &= \oint_{C_R} x \, dy \\ &= \int_{t_1}^{t_2} x \frac{dy}{dt} \, dt \\ &= \int_{t_1}^{t_2} (r \cos \theta) \left[ \frac{\partial y}{\partial r} \frac{dr}{dt} + \frac{\partial y}{\partial \theta} \frac{d\theta}{dt} \right] \, dt \\ &= \oint_{C_S} \left( \frac{r}{2} \sin 2\theta \, dr + r^2 \cos^2 \theta \, d\theta \right) \\ &= \iint_S (\tilde{Q}_r - \tilde{P}_\theta) \, dr \, d\theta \\ &= \iint_S (2r \cos^2 \theta - r \cos 2\theta) \, dr \, d\theta \\ &= \iint_S r \, dr \, d\theta \end{align*}
$$
<!--ID: 1741441681484-->
