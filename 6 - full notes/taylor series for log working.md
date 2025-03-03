2025-02-26 22:10
Status: 
Tags: [[Taylor's Theorem]]
# taylor series for log working

TD: YEAR1::TERM2::MA139 Analysis 2::04 Taylor's Theorem
Q: Use Taylor's to work out the series for log
A: Let $f:x\mapsto \log x$, then $f^{(n)}(x)=(-1)^{n-1}(n-1)!x^{-n}$. If we approximate $\log$ at $x=1$ we get $f^{(n)}(1)=(-1)^{n-1}(n-1)!$ then it follows that$$\begin{align}
\log x &= 0 + (x - 1) - \frac{(x - 1)^2}{2} +  \\
&\cdots + (-1)^{n-2} \frac{(x - 1)^{n-1}}{n - 1} + (-1)^{n-1} \frac{t^{-n} (x - 1)^n}{n} \\
&= (x - 1) - \frac{(x - 1)^2}{2} + \\
&\cdots + (-1)^{n-2} \frac{(x - 1)^{n-1}}{n - 1} + (-1)^{n-1} \frac{1}{n} \left( \frac{x - 1}{t} \right)^n
\end{align}$$for some $t\in(1,x)$. If $1 \leq x \leq 2$, then $0 < x - 1 \leq 1 \leq t$. Hence the error term is at most $\frac{1}{n}$, which tends to 0 as $n \to \infty$. This means that we can take a limit and conclude that we have an infinite series for $\log x$: $$ \log x = (x - 1) - \frac{(x - 1)^2}{2} + \frac{(x - 1)^3}{3} - \cdots $$as long as $1 \leq x \leq 2$.
<!--ID: 1740608542340-->
