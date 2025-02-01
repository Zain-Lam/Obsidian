2025-01-30 21:45
Status: 
Tags: [[Limits of functions and the derivative]]
# definition of local linearisation

TD: YEAR1::TERM2::MA139 Analysis 2::02 Limits and the derivative
Q: Define local linearisation.
?
A:If $I$ is an open interval with $f: I \to \mathbb{R}$, and $c \in I$. Then $f$ is differentiable at $c$ _iff_  $\exists A$ and a function $\varepsilon$ with the properties that  $\forall x$,
$$
f(x) - f(c) = A(x - c) + \varepsilon(x)(x - c),
$$
$\varepsilon(c) = 0$, and $\varepsilon$ is continuous at $c$ (i.e., $\varepsilon(x) \to 0$ as $x \to c$). If this happens, $A = f'(c)$.
<!--ID: 1738273699745-->
