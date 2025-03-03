2025-02-26 13:43
Status: 
Tags: [[Taylor's Theorem]]
# proof for l'Hopital's rule

TD: YEAR1::TERM2::MA139 Analysis 2::04 Taylor's Theorem
Q: Prove l'Hopital's rule
A: Suppose that $\lim_{x \to c} \frac{f'(x)}{g'(x)}$ does indeed exist. Then it cannot be that $g'(x) = 0$ at a sequence of points converging to $c$.
So there is some interval around $c$ on which $g'$ is non-zero (except perhaps at $c$ itself). So $g'$ is non-zero on an interval each side of $c$. This enables us to apply Cauchy's Mean Value Theorem. Because $f(c) = g(c) = 0$, $$ \lim_{x \to c} \frac{f(x)}{g(x)} = \lim_{x \to c} \frac{f(x) - f(c)}{g(x) - g(c)}. $$As long as $x$ is in the region around $c$ where $g' \neq 0$, Cauchy's MVT ensures that there is a point $t$ (depending upon $x$) between $c$ and $x$ where $$ \frac{f(x) - f(c)}{g(x) - g(c)} = \frac{f'(t)}{g'(t)}. $$ As $x \to c$, the corresponding $t$ is forced to approach $c$ as well, and so $$ \frac{f(x)}{g(x)} = \frac{f(x) - f(c)}{g(x) - g(c)} \to \lim_{t \to c} \frac{f'(t)}{g'(t)}. $$
<!--ID: 1740577961274-->
