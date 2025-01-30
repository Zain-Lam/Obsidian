2025-01-30 21:16
Status: 
Tags: [[Limits of functions and the derivative]]
# proof for the derivative of monomials

TD: YEAR1::TERM2::MA139 Analysis 2::02 Limits and the derivative
Q: Prove that if $n$ is a positive integer, then the derivative of $x \mapsto x^n$ is $x \mapsto nx^{n-1}$.
A: We have shown this is true for $n = 1$. Assume inductively that we have the result for $f(x) = x^n$. Then $x^{n+1} = x f(x)$, so by the product rule, its derivative is
$$
f(x) + x f'(x) = x^n + x \cdot n x^{n-1} = (n + 1)x^n,
$$
completing the inductive step.
<!--ID: 1738272114429-->
