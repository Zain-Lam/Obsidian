2025-01-30 23:11
Status: 
Tags: [[Limits of functions and the derivative]]
# proof for Rolle's Theorem

TD: YEAR1::TERM2::MA139 Analysis 2::02 Limits and the derivative
Q: Prove Rolle's Theorem.
A: If $f$ is constant on the interval, then its derivative is zero everywhere. If not, it takes values different from $f(a) = f(b)$. Assume it is larger than $f(a)$ somewhere.
Since $f$ is continuous on the closed interval, by EVT it attains its maximum value at some point $c$, and this cannot be $a$ or $b$: so $c$ lies in $(a, b)$. If $x > c$, then $f(x) - f(c) \leq 0$ while $x - c > 0$, so the ratio
$$
\frac{f(x) - f(c)}{x - c} \leq 0.
$$
So $f'(c)$ is a limit of non-positive values and so is not positive.
On the other hand, if $x < c$, then $f(x) - f(c) \leq 0$ while $x - c < 0$, so the ratio
$$
\frac{f(x) - f(c)}{x - c} \geq 0.
$$
So $f'(c)$ is a limit of non-negative values and so is not negative.
It follows that, $f'(c) = 0$. A similar proof for if it is a minimum.
<!--ID: 1738278935604-->
