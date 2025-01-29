2025-01-29 16:36
Status: 
Tags: [[Power Series]]
# characteristic property of the exponential proof

TD: YEAR1::TERM2::MA139 Analysis 2::01 Power Series 1
Q: Prove the characteristic property of the exponential.
A: By the algebra of limits it suffices to check that$$
\sum_{m=0}^{2m} \frac{(x + y)^k}{k!} - \left(\sum_{0}^{m}\frac{x^i}{i!} \right) \left(\sum_{j=0}^{m} \frac{y^j}{j!}\right) \to 0
$$because the first term converges to $e^{x+y}$ and the second to $e^{x}e^{y}$
By binomial 