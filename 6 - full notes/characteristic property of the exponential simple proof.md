2025-02-05 15:24
Status: 
Tags: [[Power Series II]] [[characteristic property of the exponential]] [[characteristic property of the exponential proof]]
# characteristic property of the exponential simple proof

TD: YEAR1::TERM2::MA139 Analysis 2::03 Power Series II
Q: Prove that if $x$ and $y$ are real numbers then $\exp(x + y) = \exp(x) \exp(y)$ using the fact that the power series is differentiable.
A: For a fixed number $z$ consider the function $x \mapsto \exp(x) \exp(z - x)$. We may differentiate this with respect to $x$ using the product rule and the chain rule to get
$$
\exp(x) \exp(z - x) - \exp(x) \exp(z - x) = 0.
$$
By the MVT the function is constant. At $x = 0$ the function is $\exp z$, so we know that for all $x$
$$
\exp(x) \exp(z - x) = \exp(z).
$$
Now if we set $z = x + y$ we get the conclusion we want.
<!--ID: 1738769466633-->

