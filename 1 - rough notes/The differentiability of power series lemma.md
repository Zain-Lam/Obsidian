2025-02-05 14:42
Status: 
Tags: [[Power Series II]]
# The differentiability of power series lemma

TD: YEAR1::TERM2::MA139 Analysis 2::03 Power Series II
Q: Let $\sum a_n x^n$ be a power series with radius of convergence $R$.
Prove that the series $\sum n a_n x^{n-1}$ has the same radius of convergence.
A: We know that the absolute series $\sum |a_n| x^n$ has the same radius of convergence as $\sum a_n x^n$. Now if $0 < x < R$ choose $y$ with $x < y < R$. Then $\sum |a_n| x^n$ and $\sum |a_n| y^n$ both converge and hence so does  
$$\sum_{n=0}^{\infty} |a_n|\frac{ (y^n - x^n)}{y - x} = \sum_{n=1}^{\infty} |a_n| (y^{n-1} + y^{n-2}x + \cdots + x^{n-1}).$$  
But the last sum is larger than $\sum_{n=1}^{\infty} |a_n| n x^{n-1}$ so the latter also converges. This means that $\sum n a_n x^{n-1}$ converges absolutely as required.
