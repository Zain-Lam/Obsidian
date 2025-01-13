2025-01-13 12:44
Status: 
Tags: [[DM2 Asymptotic notation and summations]]
# arithmetic series big theta

TD: YEAR1::TERM2::CS147 Discrete Maths 2::01 
Q: If we have two constants $a > 0, b > 0$ then what can be said about $\sum_{i=1}^{n}(ai+b)$
A: $$\begin{align}
\sum_{i=1}^{n}(ai+b)&=\sum_{i=1}^{n}ai+\sum_{i=1}^{n}b \\
&=a\frac{n(n+1)}{2}+bn \\
&=Θ(n^{2} ) + Θ(n) \\
&= Θ(n^{2} )
\end{align}$$ 
<!--ID: 1736772631383-->
