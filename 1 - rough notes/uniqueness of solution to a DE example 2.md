2025-01-30 23:03
Status: 
Tags: [[Limits of functions and the derivative]]
# uniqueness of solution to a DE example 2

TD: YEAR1::TERM2::MA139 Analysis 2::02 Limits and the derivative
Q: Prove that the only functions $f: (0, \infty) \to \mathbb{R}$ satisfying
$$
f'(x) + \frac{1}{x} f(x) = 2
$$
are the functions $f(x) = \frac{A}{x} + x$ for some constant $A$.
A: Let $g(x) = x f(x) - x^2$ for positive $x$. Then
$$
g'(x) = x f'(x) + f(x) - 2x = x \left( f'(x) + \frac{1}{x} f(x) - 2 \right) = 0.
$$
So $g$ is constant $A$ (say), and the formula for $f$ follows.
<!--ID: 1738278482682-->
