2025-01-30 23:16
Status: 
Tags: [[Limits of functions and the derivative]]
# proof for Mean Value Theorem

TD: YEAR1::TERM2::MA139 Analysis 2::02 Limits and the derivative
Q: Prove MVT
?
A:Consider the function given by
$$
g(x) = f(x) - x \cdot \frac{f(b) - f(a)}{b - a}.
$$Then we have
$$
g(b) - g(a) = f(b) - f(a) - (b - a) \cdot \frac{f(b) - f(a)}{b - a} = 0.
$$
So by Rolle’s Theorem, there is a point $c$ where $g'(c) = 0$. It follows that$$
f'(c) = \frac{f(b) - f(a)}{b - a}.
$$The intuition behind this is altering $f(x)$ to $g(x)$ where $g(x)$ is a constant function.
<!--ID: 1738279459203-->

