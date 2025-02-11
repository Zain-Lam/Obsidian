2025-02-11 11:49
Status: 
Tags: [[Integration with special coordinates]]
# polar coordinate integration example 1

TD: YEAR1::TERM2::MA144 Modelling 2::06 Integration with special coordinates
Q: Find the area in the first quadrant bounded by the polar curve $r = 1 + \cos \theta$
A: Make use of the double angle $\cos$ formula$$\begin{align*}
A &= \int_0^{\frac{\pi}{2}} \int_0^{1+\cos\theta} r \, dr \, d\theta = \int_0^{\frac{\pi}{2}} \frac{(1+\cos\theta)^2}{2} \, d\theta. \\
(1+\cos\theta)^2 &= 1 + 2\cos\theta + \cos^2\theta. \\
A &= \frac{1}{2} \int_0^{\frac{\pi}{2}} (1 + 2\cos\theta + \cos^2\theta) \, d\theta. \\
\int_0^{\frac{\pi}{2}} 1 \, d\theta &= \frac{\pi}{2}, \quad \int_0^{\frac{\pi}{2}} 2\cos\theta \, d\theta = 2, \quad \int_0^{\frac{\pi}{2}} \cos^2\theta \, d\theta = \frac{\pi}{4}. \\
A &= \frac{1}{2} \left( \frac{\pi}{2} + 2 + \frac{\pi}{4} \right) = \frac{1}{2} \left( \frac{3\pi}{4} + 2 \right) = \frac{3\pi}{8} + 1.
\end{align*}$$
<!--ID: 1739274982048-->


