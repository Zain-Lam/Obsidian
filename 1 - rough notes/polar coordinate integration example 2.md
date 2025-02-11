2025-02-11 11:59
Status: 
Tags: [[Integration with special coordinates]]
# polar coordinate integration example 2

TD: YEAR1::TERM2::MA144 Modelling 2::06 Integration with special coordinates
Q: Calculate $\iint_R xy^2 \,\mathrm{d}x \,\mathrm{d}y$ where $R$ is the region in the first quadrant bounded by concentric circles of radius $1$ and $2$, centered at the origin.
A: Using $x = r\cos\theta$ and $y = r\sin\theta$,  
$$
\begin{align*}
I &= \iint_R xy^2 \,\mathrm{d}A = \int_0^{\frac{\pi}{2}} \int_1^2 (r\cos\theta)(r\sin\theta)^{2} r \,\mathrm{d}r \,\mathrm{d}\theta \\
&= \left( \int_0^{\frac{\pi}{2}} \cos\theta \sin^2\theta \,\mathrm{d}\theta \right) \left( \int_1^2 r^4 \,\mathrm{d}r \right).
\end{align*}
$$We can split this up as the integration limits are all constants.  
$$
\begin{align*}
\int_1^2 r^4 \,\mathrm{d}r &= \left[ \frac{r^5}{5} \right]_1^2 = \frac{32}{5} - \frac{1}{5} = \frac{31}{5}, \\
\int_0^{\frac{\pi}{2}} \cos\theta \sin^2\theta \,\mathrm{d}\theta &= \int_0^{\frac{\pi}{2}} \cos\theta (1 - \cos^2\theta) \,\mathrm{d}\theta = \left[ \int_0^{\frac{\pi}{2}} \cos\theta \,\mathrm{d}\theta - \int_0^{\frac{\pi}{2}} \cos^3\theta \,\mathrm{d}\theta \right].
\end{align*}
$$  
$$
\begin{align*}
\int_0^{\frac{\pi}{2}} \cos\theta \,\mathrm{d}\theta &= \sin\theta \Big|_0^{\frac{\pi}{2}} = 1, \quad  
\int_0^{\frac{\pi}{2}} \cos^3\theta \,\mathrm{d}\theta = \left[ \frac{\sin\theta}{3} + \frac{\sin 3\theta}{9} \right]_0^{\frac{\pi}{2}} = \frac{1}{3}, \\
\int_0^{\frac{\pi}{2}} \cos\theta \sin^2\theta \,\mathrm{d}\theta &= 1 - \frac{1}{3} = \frac{2}{3}.
\end{align*}
$$  
$$
\begin{align*}
I &= \frac{2}{3} \times \frac{31}{5} = \frac{62}{15}.
\end{align*}
$$  
