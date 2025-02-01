2025-02-01 14:23
Status: 
Tags: [[Differentiation and arc length]] [[definition of the derivative]] [[vector-valued function as its components]]
# definition of derivative of a vector valued function

TD: YEAR1::TERM2::MA144 Modelling 2::02 Differentiation and arc length
Q: How do we define the derivative of a vector valued function $\underline{r}$ at $t=c$? and what does it mean?
A: We treat it similarly$$\begin{align}
\underline{r}'(c)&=\lim_{\Delta t \to 0} \frac{\underline{r}(c + \Delta t) - \underline{r}(c)}{\Delta t} \\
&=\left(\lim_{\Delta t \to 0} \frac{r_{1}(c + \Delta t) - r_{1}(c)}{\Delta t},\dots,\lim_{\Delta t \to 0} \frac{r_{n}(c + \Delta t) - r_{n}(c)}{\Delta t} \right) \\
&=\left(r_{1}'(c),\dots,r_{n}'(c)\right)
\end{align}
$$So we just differentiate each component in the usual way.
The vector $\mathbf{r}(c)$ is a tangent vector to the curve at $t=c$.
<!--ID: 1738420270508-->
