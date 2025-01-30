2025-01-30 22:17
Status: 
Tags: [[Limits of functions and the derivative]]
# functions with positive derivative

TD: YEAR1::TERM2::MA139 Analysis 2::02 Limits and the derivative
Q: Prove that if $f: I \to \mathbb{R}$ is differentiable on the open interval $I$ and $f'(x) > 0$ for all $x$ in the interval, then $f$ is strictly increasing on the interval.
A: Suppose for contradiction, $\exists a,b$ with $a < b$ but $f(a) \geq f(b)$, then by MVT we could find a point $c$ where
$$
f'(c) = \frac{f(b) - f(a)}{b - a} \leq 0,
$$
contradicting the hypothesis.
<!--ID: 1738275542431-->
