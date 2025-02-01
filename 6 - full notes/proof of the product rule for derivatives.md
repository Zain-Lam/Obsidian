2025-01-30 16:54
Status: 
Tags: [[Limits of functions and the derivative]]
# proof of the product rule for derivatives

TD: YEAR1::TERM2::MA139 Analysis 2::02 Limits and the derivative
Q: Prove the product rule for differentiation.
?
A:$$
\begin{align*}
\frac{f(x)g(x) - f(c)g(c)}{x - c} &= \frac{(f(x) - f(c))g(x) + f(c)(g(x) - g(c))}{x - c} \\
&= \frac{f(x) - f(c)}{x - c}g(x) + f(c) \frac{g(x) - g(c)}{x - c}.
\end{align*}
$$The algebra of limits tells us that as $x \to c$, this expression approaches
$$
f'(c)g(c) + f(c)g'(c)
$$
Note, we need to use continuity of $g$ at $c$ to write $g(x)\to g(c)$ as $x \to c$.
<!--ID: 1738256549670-->
