2025-02-26 14:12
Status: 
Tags: [[Taylor's Theorem]]
# proof for Taylor's Theorem, Lagrange Remainder

TD: YEAR1::TERM2::MA139 Analysis 2::04 Taylor's Theorem
Q: Proof for Taylor's Theorem Lagrange remainder using $g(x)$
A: The function $g$ given by $g(x)=$$$f(x) - \left( f(a) + f'(a)(x - a) + \cdots + \frac{f^{(n-1)}(a)}{(n - 1)!}(x - a)^{n-1} \right) $$satisfies $g(a) = 0$, $g'(a) = 0$, and so on up to $g^{(n-1)}(a) = 0$. It also satisfies $g^{(n)}(x) = f^{(n)}(x)$ for all $x$ because $f$ and $g$ differ by a polynomial of degree only $n - 1$. If we put $$ h(x) = g(x) - \frac{g(b)}{(x - a)^n (b - a)^n} $$then $h$ also has its first $n-1$ derivatives vanishing at $a$, but in addition, it satisfies $h(b) = 0$. We now proceed inductively. Since $h(b) = h(a) = 0$, there is a point $t_1$ in $(a, b)$ where $h'(t_1) = 0$ by Rolle’s Theorem. Since $h'(t_1) = h'(a) = 0$, there is a point $t_2$ in $(a, t_1)$ with $h''(t_2) = 0$. Continuing in this way, we eventually get a point $t = t_n$ where $h^{(n)}(t) = 0$. In terms of $g$, this says that $$ g^{(n)}(t) = \frac{g(b)}{n!(b - a)^n}. $$ Since $g(x)=$$$f(x) - \left( f(a) + f'(a)(x - a) + \cdots + \frac{f^{(n-1)}(a)}{(n - 1)!}(x - a)^{n-1} \right), $$ we have $$ g(b) = \frac{g^{(n)}(t)}{n!(b - a)^n} = \frac{f^{(n)}(t)}{n!(b - a)^n}. $$ Thus, $$\begin{align}
&f(b) - \left( f(a) + f'(a)(b - a) + \cdots + \frac{f^{(n-1)}(a)}{(n - 1)!}(b - a)^{n-1} \right) \\
&= \frac{f^{(n)}(t)}{n!}(b - a)^n,
\end{align}$$which is exactly the statement of the theorem.
<!--ID: 1740581151604-->
