2025-02-02 13:15
Status: 
Tags: [[Differentiation and arc length]]
# unit speed arc length parametrisation

TD: YEAR1::TERM2::MA144 Modelling 2::02 Differentiation and arc length
Q: Let $\tilde{\mathbf{r}}(s)$ be the arc-length parametrisation of a curve parametrised by $\mathbf{r}(t)$. Suppose that $|\mathbf{r}'(t)| \neq 0$, then prove $\tilde{\mathbf{r}}(s)$ has unit speed.
A: To show $\tilde{\mathbf{r}}(s)$ has unit speed we need $|\tilde{\mathbf{r}}'(s)|=1$. We know $s$ is a function of $t$. so we can rearrange $\tilde{\mathbf{r}}(s) = \mathbf{r}(t(s))$, then we apply chain rule $$
\frac{d\tilde{\mathbf{r}}}{ds} = \frac{d\mathbf{r}}{dt}\cdot\frac{dt}{ds} 
$$and we know that $\frac{ds}{dt}=|\mathbf{r}'(t)|$ so we can substitute in the reciprocal when finding the absolute value of $\frac{d\tilde{\mathbf{r}}}{ds}$ so we get $$\frac{d\tilde{\mathbf{r}}}{ds} = \mathbf{r}'(t)\cdot\frac{1}{|\mathbf{r}'(t)|}=1
$$as required.
<!--ID: 1738504622823-->

