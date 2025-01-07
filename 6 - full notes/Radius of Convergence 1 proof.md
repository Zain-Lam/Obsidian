2025-01-06 17:12
Status: 
Tags: [[Power Series]]
# Radius of Convergence 1

TD: YEAR1::TERM2::MA139 Analysis 2::01 Power Series 1
Q: Prove the Radius of Convergence Theorem 1
A: Since $\sum^{\infty}_{n=0}a_{n}t^{n}$  converges, we know that $a_{n}t^n\to{0}$ as $n\to \infty$ so the sequence is bounded. There is some $M$ for which $|a_{n}t^n|<M \forall n$ 
Now $$\begin{align*} \sum_{n=0}^{N} |a_n x^n| &= \sum_{n=0}^{N} |a_n t^n| \left| \frac{x}{t} \right|^n \\ &\leq M \sum_{n=0}^{N} \left| \frac{x}{t} \right|^n \\ &\leq M \sum_{n=0}^{\infty} \left| \frac{x}{t} \right|^n \\ &= M \cdot \frac{1}{1 - \left| \frac{x}{t} \right|} \end{align*}$$ Hence $\sum^{\infty}_{n=0}|a_{n}t^{n}|<\infty$ and the series converges absolutely.
<!--ID: 1736184682022-->
