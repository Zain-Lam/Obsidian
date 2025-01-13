2025-01-13 13:14
Status: 
Tags: [[DM2 Asymptotic notation and summations]]
# example of bounding a sum for Theta notation

TD: YEAR1::TERM2::CS147 Discrete Maths 2::02
Q: consider $f(n) = \sum_{i=1}^{n} i^3$ . Prove that $f(n) = Θ(n^4 )$.
A: upper bound:
$f(n) = \sum_{i=1}^{n} i^3\leq \sum_{i=1}^{n} n^3= \mathcal O(n^{4})$
lower bound:
$f(n) = \sum_{i=1}^{n} i^3 \geq \sum_{i=\frac{n}{2}}^{n} \left(\frac{n}{2}\right)^3 = \Omega(n^4)$
so we have $f(n) = Θ(n^4 )$.
<!--ID: 1736775700882-->


