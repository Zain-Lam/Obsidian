2025-01-13 12:59
Status: 
Tags: [[DM2 Asymptotic notation and summations]]
# harmonic series big theta

TD: YEAR1::TERM2::CS147 Discrete Maths 2::01 
Q: What is the Theta for the harmonic series $\sum_{i=1}^{n} \frac{2n}{i}$
?
A:$$\begin{align}
\sum_{i=1}^{n} \frac{2n}{i} &= \Theta\left(\sum_{i=1}^{n}\frac{n}{i} \right) \\
&=\Theta\left(n\sum_{i=1}^{n}\frac{1}{i} \right) \\
&=Θ(n \log n).
\end{align}$$
<!--ID: 1736773962111-->
