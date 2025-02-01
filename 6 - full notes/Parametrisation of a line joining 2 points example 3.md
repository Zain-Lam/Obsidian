2025-01-31 12:42
Status: 
Tags: [[Curves and their Parametrisations]]
# Parametrisation of a line joining 2 points example 3

TD: YEAR1::TERM2::MA144 Modelling 2::01 Curves and their parametrisations 
Q: Let $\mathbf{a}$ and $\mathbf{b}$ be the position vectors of points $A$ and $B$. Parametrise the line, beginning at $A$ and ending at $B$ with the parameter $v\in[-1,1]$.
?
A:We can transform $0\leq t\leq 1 \overset{\times 2, -1}{\longrightarrow} -1\leq 2t-1 \leq 1$, then let$$
\begin{align}
v &= 2 t - 1 \\
t &= \frac{v+1}{2}
\end{align}
$$then sub this into the equation we have for $t\in[0,1]$ giving us$$\underline{r}(v)=(\underline{b}-\underline{a}) \frac{v+1}{2}+\underline{a}$$Once again we can check $\mathbf{r}(-1)=\mathbf{a}$ and $\mathbf{r}(1)=\mathbf{b}$ as required.
<!--ID: 1738340412446-->
