2025-01-11 20:22
Status: 
Tags:  [[g(n) in big O of f(n)]]
# proof that n^3 is not in big O of n

TD: YEAR1::TERM2::CS147 Discrete Maths 2::01 
Q: Prove that the function $n^3$ is not in $\mathcal O(n)$.
A: Using a proof by contradiction
Suppose that there exist constants $c > 0$ and $N$ such that $n^3 ≤ cn \forall n > N$, but we have $n^3 > cn \forall n > \sqrt{ c }$.
This leads to a contradiction, and concludes the proof.
<!--ID: 1736627236892-->
