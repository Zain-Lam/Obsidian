2025-02-21 12:52
Status: 
Tags: [[Integration with special coordinates]]
# spherical coordinates example 1

TD: YEAR1::TERM2::MA144 Modelling 2::06 Integration with special coordinates
Q: Work out the volume of a sphere of radius $a$ using a triple integral
A: We write this as the triple integral $$\begin{align}
&\int\limits_0^{\pi} \int\limits_0^{2\pi} \int\limits_0^a r^{2}\sin \phi \, \mathrm{d}r \, \mathrm{d}\theta \, \mathrm{d}\phi \\
&=\left(\int\limits_0^{\pi}\sin \phi\mathrm{d}\phi\right)\left(\int\limits_0^{2\pi}\mathrm{d}\theta\right)\left(\int\limits_0^{a}r^{2}\mathrm{d}r\right) \\
&=2\cdot2\pi \cdot \frac{a^{3}}{3} \\
&=\frac{4\pi r^{3}}{3}
\end{align}
$$which is consistent with our known formula.
<!--ID: 1740142875236-->
