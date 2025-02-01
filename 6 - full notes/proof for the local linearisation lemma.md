2025-01-30 21:51
Status: 
Tags: [[Limits of functions and the derivative]]
# proof for the local linearisation lemma

TD: YEAR1::TERM2::MA139 Analysis 2::02 Limits and the derivative
Q: Prove the local linearisation lemma
?
A:If the condition holds, then  we divide through by $(x-c)$, given $x\neq c$, then
$$
\frac{f(x) - f(c)}{x - c} = A + \varepsilon(x),
$$
and this approaches $A$ as $x \to c$. Hence, $f$ is differentiable with derivative $f'(c) = A$.
On the other hand, suppose $f$ is differentiable at $c$. Set $A = f'(c)$ and define $\varepsilon$ as follows:
$$
\varepsilon(x) = 
\begin{cases}
\frac{f(x) - f(c)}{x - c} - A & \text{if } x \neq c, \\
0 & \text{if } x = c.
\end{cases}
$$
If $x \neq c$, then $f(x) - f(c) = A(x - c) + \varepsilon(x)(x - c)$ holds because of the way $\varepsilon$ is defined, while if $x = c$, the formula is obvious. To check that $\varepsilon(x) \to 0$ as $x \to c$, observe that
$$
\lim_{x \to c} \varepsilon(x) = \lim_{x \to c} \left( \frac{f(x) - f(c)}{x - c} - f'(c) \right) = 0.
$$
<!--ID: 1738274323065-->

