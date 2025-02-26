2025-02-26 12:54
Status: 
Tags: [[Taylor's Theorem]]
# proof for cauchy's mean value theorem

TD: YEAR1::TERM2::MA139 Analysis 2::04 Taylor's Theorem
Q: Prove Cauchy's MVT
A: Consider the function $x \mapsto h(x) = f(x)(g(b) - g(a)) - (f(b) - f(a))g(x)$
At $x = a$ the value of the function is $$\begin{align}
h(a) &= f(a)g(b) - f(a)g(a) - f(b)g(a) + f(a)g(a)  \\
&= f(a)g(b) - f(b)g(a)
\end{align}$$and similarly $$\begin{align}
h(b) &= f(b)g(b) - f(b)g(a) - f(b)g(b) + f(a)g(b) \\
&= f(a)g(b) - f(b)g(a)
\end{align}$$So $h(b) = h(a)$ and by Rolle's Theorem there is a point $t$ between $a$ and $b$ where $h'(t) = 0$. Thus we have $$ h(x) = f(x)(g(b) - g(a)) - (f(b) - f(a))g(x) $$and there is a point $t$ where $h'(t) = 0$. But this means that $$ f'(t)(g(b) - g(a)) = (f(b) - f(a))g'(t). $$Since $g'$ is non-zero on $(a, b)$, Rolle's Theorem applied to $g$ shows that $g(b) - g(a) \neq 0$ as well, and we can rearrange to get the conclusion of the theorem.
<!--ID: 1740576506905-->
