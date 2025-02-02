2025-02-02 14:28
Status: 
Tags: [[Differentiation and arc length]] [[unit speed arc length parametrisation]]
# unit speed parametrisation relationships

TD: YEAR1::TERM2::MA144 Modelling 2::02 Differentiation and arc length
Q: Let $\mathbf{\underline{r}}(u)$ be a unit speed parametrisation of a curve. Let $\tilde{\mathbf{r}}(s)$ be its arc-length parametrisation.  
Find a relation between $\mathbf{u}$ and $s$.
A: By the chain rule we get $$
\frac{d\tilde{\mathbf{r}}}{ds} = \frac{d\mathbf{\underline{r}}}{du} \cdot \frac{du}{ds}
$$then when we take the length we get $$
\begin{align*}
\left|\frac{d\tilde{\mathbf{r}}}{ds}\right| 
&= \left|\frac{d\mathbf{\underline{r}}}{du}\right| \cdot \left|\frac{du}{ds}\right|\\
\underbrace{1}_{\mathclap{\left|\frac{d\tilde{\mathbf{r}}}{ds}\right|=1}}&=1\cdot \left|\frac{du}{ds}\right|\\ \\
\left|\frac{du}{ds}\right|&=1
\end{align*}
$$
so we get that $u=\pm s +c$ where $c$ is just a shift in the parameter value, and the $\pm$ is change in orientation.
<!--ID: 1738507390484-->
