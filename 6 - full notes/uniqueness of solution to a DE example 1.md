2025-01-30 22:54
Status: 
Tags: [[Limits of functions and the derivative]]
# uniqueness of solution to a DE example 1

TD: YEAR1::TERM2::MA139 Analysis 2::02 Limits and the derivative
Q: Prove that the only functions $f: \mathbb{R} \to \mathbb{R}$ satisfying
$$
f'(x) = f(x)
$$
are the functions $f(x) = A e^x$ for some constant $A$
A: Since $e^x$ is differentiable and is its own derivative. Suppose $f$ is such a solution, and let $g(x) = e^{-x} f(x)$.
Then, by the chain rule, we have
$$
g'(x) = -e^{-x} f(x) + e^{-x} f'(x) = e^{-x} \big( -f(x) + f'(x) \big) = 0.
$$
By the corollary, since the derivative of $g$ is always $0$, $g$ is a constant function with value $A$ (say). Then, $f(x) = e^x g(x) = A e^x$.
<!--ID: 1738278095807-->
