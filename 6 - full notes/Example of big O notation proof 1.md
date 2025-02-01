2025-01-13 11:59
Status: 
Tags: [[g(n) in big O of f(n)]] [[DM2 Asymptotic notation and summations]]
# Example of big O notation proof

TD: YEAR1::TERM2::CS147 Discrete Maths 2::01 
Q: Given $f(n) = 2^{\sqrt {\ln n}}$ and $g(n) = n^{0.0001}$, check $f(n) = \mathcal O(g(n))$ and $f(n) \neq Ω(g(n))$
A: We prove $f(n) = \mathcal O(g(n))$, by definition, we need to find $c > 0$ and $n > N$ such that $f(n) ≤ cg(n)$. Here we assume $c ≥ 1$ without loss of generality. then:
$$\begin{align}
2^\sqrt{ \ln_{2} }≤ cn^{0.0001} &⇔ \sqrt{ \ln 2 } ≤ \ln c + 0.0001 \ln n \\
&⇐ \sqrt{ \ln 2 } ≤ 0.0001 \ln n \\
&⇔ \sqrt{ \ln 2 } ≥ 10^4 \ln 2 ⇔ n ≥ e^{{10}^{8(\ln 2)^{2}}} := N
\end{align}$$
Conclude the proof by taking $c \geq 1$ and $N=e^{{10}^{8(\ln 2)^{2}}}$ 
<!--ID: 1736770745516-->
