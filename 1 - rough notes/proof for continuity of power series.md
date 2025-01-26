2025-01-26 14:23
Status: 
Tags: [[Power Series]]
# proof for continuity of power series

TD: YEAR1::TERM2::MA139 Analysis 2::01 Power Series 1
Q: Prove the continuity of power series theorem
A: Suppose $−R < x < R$. WTS that the function is cts at $x$.
Choose $T$ with $|x| < T < R$. Then the series $\sum |a_{n}|T^{n}$ converges, so for each $ε > 0$ there is some number N for which $\sum^∞_{N+1} |a_n| T^n < \frac{ε}{3}$.
Now if $\lvert y - x \rvert < T - \lvert x \rvert$ we will have $\lvert y \rvert < T$ as well as $\lvert x \rvert < T$. Hence
$\sum_{n=N+1}^\infty \lvert a_n \rvert \lvert x \rvert^n < \epsilon/3$ and $\sum_{n=N+1}^\infty \lvert a_n \rvert \lvert y \rvert^n < \epsilon/3$
The partial sum $\sum_{n=0}^N a_n y^n$ is a polynomial in $y$ and polynomials are continuous so there is some $\delta_0 > 0$ with the property that if $\lvert y - x \rvert < \delta_0$
$$
\left\lvert \sum_{n=0}^N a_n y^n - \sum_{n=0}^N a_n x^n \right\rvert < \epsilon/3
$$

Therefore if we choose $\delta$ to be the smaller of $\delta_0$ and $T - \lvert x \rvert$ then if $\lvert y - x \rvert < \delta$ we get
$$
\left\lvert \sum_{n=0}^\infty a_n y^n - \sum_{n=0}^\infty a_n x^n \right\rvert
\leq \left\lvert \sum_{n=N+1}^\infty a_n y^n \right\rvert
+ \left\lvert \sum_{n=0}^N a_n y^n - \sum_{n=0}^N a_n x^n \right\rvert
+ \left\lvert \sum_{n=N+1}^\infty a_n x^n \right\rvert.
$$

$$
\leq \sum_{n=N+1}^\infty \lvert a_n \rvert \lvert y \rvert^n
+ \left\lvert \sum_{n=0}^N a_n y^n - \sum_{n=0}^N a_n x^n \right\rvert
+ \sum_{n=N+1}^\infty \lvert a_n \rvert \lvert x \rvert^n < \epsilon.
$$
