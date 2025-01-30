2025-01-30 21:59
Status: 
Tags: [[Limits of functions and the derivative]]
# proof of the chain rule for derivatives

TD: YEAR1::TERM2::MA139 Analysis 2::02 Limits and the derivative
Q: Using the local linearisation lemma, prove the chain rule.
A: $f$ is differentiable at $g(c)$, so for all $y$,
$$
f(y) - f(g(c)) = f'(g(c))(y - g(c)) + \varepsilon(y)(y - g(c)),
$$
where $\varepsilon(g(c)) = 0$ and $\varepsilon$ is continuous at $g(c)$. Hence,
$$
f(g(x)) - f(g(c)) = f'(g(c))(g(x) - g(c)) + \varepsilon(g(x))(g(x) - g(c)).
$$
Consequently, if $x \neq c$,
$$
\frac{f(g(x)) - f(g(c))}{x - c} = f'(g(c)) \cdot \frac{g(x) - g(c)}{x - c} + \varepsilon(g(x)) \cdot \frac{g(x) - g(c)}{x - c}.
$$
As $x \to c$,
$$
\frac{g(x) - g(c)}{x - c} \to g'(c),
$$
while $\varepsilon \circ g$ is continuous at $c$, so $\varepsilon(g(x)) \to \varepsilon(g(c)) = 0$. Hence,
$$
\frac{f(g(x)) - f(g(c))}{x - c} \to f'(g(c)) \cdot g'(c),
$$
as required.
<!--ID: 1738274922543-->
