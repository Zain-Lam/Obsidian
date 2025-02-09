2025-02-07 16:15
Status: 
Tags: [[Cartesian Coordinates]]
# double integral example 1

TD: YEAR1::TERM2::MA144 Modelling 2::05 Cartesian Coordinates
Q: Write down the area between the curve $y = x^2$ and $y = 2x$ as a double
integral with $\mathrm{d}y \, \mathrm{d}x$ and evaluate it.
A: First we note the lines intersect at $x=0,2$ so $x$ sweeps from $0$ to $2$
then at a particular $y$ value the area is from $2x$ to $x^{2}$ giving us the double integral $$
\begin{align}
A &= \int_{x=0}^{2} \int_{y=x^{2}}^{2x} \mathrm{d}y \, \mathrm{d}x \\
&= \int_{0}^{2} 2x-x^{2} \, \mathrm{d}x \\
&=\left[ x^{2}-\frac{x^{3}}{3} \right]^{2}_{0}=\frac{4}{3}
\end{align}
$$This could also be done with $\mathrm{d}x\mathrm{d}y$.
<!--ID: 1738945544412-->
