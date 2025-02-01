2025-02-01 15:41
Status: 
Tags: [[Differentiation and arc length]] [[product rule for differentiating dotted vector-valued functions]]
# using differentiation rules for vectors example 1

TD: YEAR1::TERM2::MA144 Modelling 2::02 Differentiation and arc length
Q: Find the derivative of $f(t) = |\mathbf{r}(t)|$ (assuming that $f(t) \neq 0$)
A: $$
\begin{align*}
f^2(t) &= |\mathbf{r}|^2 \quad= \mathbf{r} \cdot \mathbf{r} \\
\frac{d}{dt} \left[ f^2(t) \right] &= \frac{d}{dt} \left[ \mathbf{r} \cdot \mathbf{r} \right] \\
2 f(t) f'(t) &= 2 \mathbf{r}' \cdot \mathbf{r} + 2 \mathbf{r} \cdot \mathbf{r}' \\
&= 2 \left( \mathbf{r}' \cdot \mathbf{r} \right) \\
f' &= \frac{\mathbf{r}' \cdot \mathbf{r}}{|\mathbf{r}|}
\end{align*}
$$We can see the key to doing this is by expanding out the modulus.
<!--ID: 1738425045527-->
