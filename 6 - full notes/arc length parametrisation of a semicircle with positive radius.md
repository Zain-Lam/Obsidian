2025-02-02 13:57
Status: 
Tags: [[Differentiation and arc length]]
# arc length parametrisation of a semicircle with positive radius

TD: YEAR1::TERM2::MA144 Modelling 2::02 Differentiation and arc length
Q: Find the arc-length parametrisation of the semicircle radius $R > 0$:  
$\{(x, y) : x^2 + y^2 = R^2, y > 0\}$.
A: First we parametrise the curve
$\mathbf{\underline{r}}(t)=(R\cos t,T\sin t),\quad t\in[0,\pi]$, then we have to find the arc-length function
$\mathbf{\underline{r}}'(t)=(-R\sin t,R\cos t)\implies |\mathbf{\underline{r}}'(t)|=R$ so the arc-length function is $$
s(t) =\int_{0}^{t}R\ du=Rt\implies t=\frac{s}{R}
$$so the arc length parametrisation is given by $$
\mathbf{\underline{\tilde{r}}}(s)=\left( R\cos \frac{s}{R},R\sin \frac{s}{R} \right),\quad s \in[0,R\pi]
$$
<!--ID: 1738505169977-->
