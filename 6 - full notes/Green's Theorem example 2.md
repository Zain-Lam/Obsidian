2025-03-08 13:14
Status: 
Tags: [[Green's and Stokes' Theorems]]
# Green's Theorem example 2

TD: YEAR1::TERM2::MA144 Modelling 2::08 Green's and Stokes
Q: Evaluate $I = \oint_{C} (y^2 \, dx + xy \, dy)$ where $C$ is the triangle $OAB$ with vertices at $O(0, 0)$, $A(1, 0)$, $B(1, 2)$, do this directly.
A: Direct calculation: $$ \int_{OA} + \int_{AB} + \int_{BO} (y^2 \, dx + x \, y \, dy) $$OA: $y=0$, $dy=0$ so $\int_{OA} (y^2 \, dx + x \, y \, dy) = 0$
AB: $x=1$, $dx=0$ so $\int_{AB} (y^2 \, dx + x \, y \, dy) = \int_0^2 y \, dy = 2$
BO: Parametrize line as $\mathbf{r}(t) = (-t, -2t)$, $t \in [-1, 0]$
Then $$
\begin{align*} \int_{BO} \left( y^2 \frac{dx}{dt} + x y \frac{dy}{dt} \right) dt &= \int_{-1}^0 (4t^2(-1) + 2t^2(-2)) \, dt \\ &= -8 \int_{-1}^0 t^2 \, dt \\ &= -\frac{8}{3} \\ &= -\frac{2}{3} \end{align*}
$$
<!--ID: 1741440384142-->
