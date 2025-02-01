2025-01-31 21:21
Status: 
Tags: [[Power Series]]
# proof for the derivative of inverses

TD: YEAR1::TERM2::MA139 Analysis 2::01 Power Series 1
Q: Prove the derivatives of inverses theorem.
A: Since $f$ has positive derivative, it is continuous and strictly increasing. Therefore, it
has a continuous inverse. Let $(c, d)$ be the range of $f$, let $x$ be in the interval $(c, d)$, and $g(x) = y$. We want to calculate
$$
\lim_{u \to x} \frac{g(u) - g(x)}{u - x}.
$$
Let $v = g(u)$ so that $u = f(v)$. Then the quotient is
$$
\frac{v - y}{f(v) - f(y)}.
$$
As $u \to x$, we know that $v = g(u) \to y = g(x)$ because $g$ is continuous at $x$. So we want to calculate
$$
\lim_{v \to y} \frac{v - y}{f(v) - f(y)}.
$$
We know that
$$
\lim_{v \to y} \frac{f(v) - f(y)}{v - y} = f'(y)
$$
and that this limit is positive. So by the properties of limits, we have
$$
\lim_{u \to x} \frac{g(u) - g(x)}{u - x} = \lim_{v \to y} \frac{v - y}{f(v) - f(y)} = \frac{1}{f'(y)} = \frac{1}{f'(g(x))}.
$$
<!--ID: 1738358580188-->

