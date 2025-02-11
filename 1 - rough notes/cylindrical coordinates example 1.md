2025-02-11 12:22
Status: 
Tags: [[Integration with special coordinates]]
# cylindrical coordinates example 1

TD: YEAR1::TERM2::MA144 Modelling 2::06 Integration with special coordinates
Q: Find the volume of a cylinder with base radius $a$ and height $h$
A: We can write this as the triple integral $$
\int\limits_0^{2\pi} \int\limits_0^a \int\limits_0^h r \, \mathrm{d}z \, \mathrm{d}r \, \mathrm{d}\theta
$$which can be broken up easily as all the integration limits are constants$$
\begin{align}
&=\left( \int\limits_0^{2\pi} \mathrm{d}\theta \right) \left( \int\limits_0^a r \, \mathrm{d}r \right) \left( \int\limits_0^h \mathrm{d}z \right) \\
&=2\pi \cdot \frac{a^{2}}{2}\cdot h \\
&=\pi a^{2}h
\end{align}
$$which is consistent with the formula we know.
<!--ID: 1739277772198-->
