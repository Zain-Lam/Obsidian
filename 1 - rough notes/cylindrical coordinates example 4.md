2025-02-20 22:23
Status: 
Tags: [[Integration with special coordinates]]
# cylindrical coordinates example 4

TD: YEAR1::TERM2::MA144 Modelling 2::06 Integration with special coordinates
Q: Find the $z$ coordinate, $\bar{z}$, of the center of mass of the solid bounded by the surface $z = 1 - x^2 - y^2$ and the $xy$-plane. Assume that the density $\varepsilon$ is constant.
A: Recall that $$
\bar{z} = \frac{1}{M} \iiint\limits_{\Omega} \rho z \, \mathrm{d}V
=\frac{\iiint \cancel{\rho} z \, \mathrm{d}V}{\iiint \cancel{\rho} \, \mathrm{d}V}
$$First calculate the volume $$
\begin{align}
V=\iiint \, \mathrm{d}V &= \int\limits_0^{2\pi} \int\limits_0^1 \int\limits_0^{1-r^{2}} r \, \mathrm{d}z \, \mathrm{d}r \, \mathrm{d}\theta \\
&=\frac{\pi}{2}
\end{align}
$$Then the 'weighting' of $z$ which comes to $\frac{\pi}{6}$ so the centre of mass is at $\frac{1}{3}$
<!--ID: 1740090820952-->

