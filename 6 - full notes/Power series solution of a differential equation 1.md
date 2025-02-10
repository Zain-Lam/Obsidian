2025-02-09 14:23
Status: 
Tags: [[Power Series II]]
# Power series solution of a differential equation 1

TD: YEAR1::TERM2::MA139 Analysis 2::03 Power Series II
Q: Let $f$ be defined on $(-1,1)$ by the series$f(x) = \sum_{n=1}^{\infty} \frac{x^n}{n^2}$ Then prove that $f$ satisfies the differential equation $x f''(x) + f'(x) = \frac{1}{1 - x}$
A: The series has radius of convergence 1 and the derivatives are as follows
$$
\begin{align}
f'(x) &= \sum_{n=1}^{\infty} \frac{n x^{n-1}}{n^2} \\
f''(x) &= \sum_{n=1}^{\infty} \frac{n (n-1) x^{n-2}}{n^2}
\end{align}
$$noting that the $n$ for the second sum should be from $2$ but this is strategic as
$$xf''(x) = \sum_{n=1}^{\infty} \frac{(n-1)x^{n-1}}{n}$$So it follows that $$xf''(x) + f'(x) = \sum_{n=1}^{\infty} \frac{n x^{n-1}}{n} = \sum_{n=1}^{\infty} x^{n-1} = \frac{1}{1-x}$$
<!--ID: 1739111056509-->

