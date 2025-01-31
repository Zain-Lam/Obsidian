2025-01-31 11:35
Status: 
Tags: [[Curves and their Parametrisations]]
# Parametrisation of a line joining 2 points example 1

TD: YEAR1::TERM2::MA144 Modelling 2::01 Curves and their parametrisations 
Q: Let $\mathbf{a}$ and $\mathbf{b}$ be the position vectors of points $A$ and $B$. Parametrise the line, beginning at $A$ and ending at $B$ with the parameter $u\in[0,2\pi]$
A: We can transform $0\leq t\leq 1 \overset{\times 2\pi}{\longrightarrow} 0\leq 2\pi t \leq 2\pi$, then let$$
\begin{align}
u &= 2\pi t \\
t &= \frac{u}{2\pi}
\end{align}
$$then sub this into the equation we have for $t\in[0,1]$ giving us$$\underline{r}(u)=(\underline{b}-\underline{a}) \frac{u}{2\pi }+\underline{a}$$Once again we can check $\mathbf{r}(0)=\mathbf{a}$ and $\mathbf{r}(2\pi)=\mathbf{b}$ as required.
<!--ID: 1738326766704-->
