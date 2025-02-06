2025-02-05 14:49
Status: 
Tags: [[Power Series II]]
# The differentiability of power series theorem

TD: YEAR1::TERM2::MA139 Analysis 2::03 Power Series II
Q: Let $f(x) = \sum a_n x^n$ be a power series with radius of convergence $R$.
Then prove that $f$ is differentiable on $(-R, R)$ and  
$$f'(x) = \sum_{n=1}^{\infty} n a_n x^{n-1}.$$
A: Choose $T$ with $|x| < T < R$. We know from the lemma that the series $\sum n|a_n|T^{n-1}$ converges, so given $\epsilon > 0$ there is a number $N$ so that  
$$\sum_{n=N+1}^{\infty} n|a_n|T^{n-1} < \frac{\varepsilon}{3}.$$
Now if $0 < |y - x| < T - |x|$, we have $|y| < T$ as well as $|x| < T$, and so  
$$\left| \sum_{n=N+1}^{\infty} n a_n x^{n-1} \right| \leq \sum_{n=N+1}^{\infty} n |a_n| |x|^{n-1} < \frac{\varepsilon}{3}.$$and also,$$
\begin{align*}
\left| \sum_{n=N+1}^{\infty} a_n \frac{y^n - x^n}{y - x} \right| &= \left| \sum_{n=N+1}^{\infty} a_n (y^{n-1} + y^{n-2}x + \dots + x^{n-1}) \right| \\
&\leq \sum_{n=N+1}^{\infty} |a_n| (|y|^{n-1} + \dots + |x|^{n-1}) \\
&\leq \sum_{n=N+1}^{\infty} n|a_n| T^{n-1} < \frac{\varepsilon}{3}.
\end{align*}
$$The sum$$\sum_{n=1}^{N} a_n (y^{n-1} + y^{n-2}x + \dots + x^{n-1})$$is a polynomial in $y$ whose value at $x$ is $\sum_{n=1}^{N} n a_n x^{n-1}$, so there is a $\delta_0 > 0$ with the property that if $0 < |y - x| < \delta_0$, then$$
\begin{align*}
&\left| \sum_{n=1}^{N} a_n \frac{y^n - x^n}{y - x} - \sum_{n=1}^{N} n a_n x^{n-1} \right| \\
&= \left| \sum_{n=1}^{N} a_n (y^{n-1} + y^{n-2}x + \dots + x^{n-1}) - \sum_{n=1}^{N} n a_n x^{n-1} \right| \\
&< \frac{\varepsilon}{3}.
\end{align*}
$$So if we choose $\delta$ to be the smaller of $\delta_0$ and $T - |x|$, then whenever $0 < |y - x| < \delta$,$$
\begin{align*}
\left| \sum_{n=1}^{\infty} a_n \frac{y^n - x^n}{y - x} - \sum_{n=1}^{\infty} n a_n x^{n-1} \right|
&\leq \left| \sum_{n=N+1}^{\infty} a_n \frac{y^n - x^n}{y - x} \right| \\
&\quad + \left| \sum_{n=1}^{N} a_n \frac{y^n - x^n}{y - x} - \sum_{n=1}^{N} n a_n x^{n-1} \right| \\
&\quad + \left| \sum_{n=N+1}^{\infty} n a_n x^{n-1} \right| \\
&< \varepsilon.
\end{align*}
$$
<!--ID: 1738767725965-->

