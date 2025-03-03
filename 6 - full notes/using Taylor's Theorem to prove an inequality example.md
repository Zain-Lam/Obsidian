2025-02-26 14:52
Status: 
Tags: [[Taylor's Theorem]]
# using Taylor's Theorem to prove an inequality example

TD: YEAR1::TERM2::MA139 Analysis 2::04 Taylor's Theorem
Q: Using Taylor's prove that if $0 \leq x \leq \pi$, then $\sin x \leq x$.
A: Let $f(x) = \sin x$. We have $f'(x) = \cos x$ and $f''(x) = -\sin x$. So $f(0) = 0$, $f'(0) = 1$, and by Taylor’s Theorem with $n = 2$,$$ f(x) = f(0) + f'(0)x + \frac{f''(t)}{2}x^2. $$This says $$ \sin x = 0 + x - \frac{\sin t}{2}x^2 $$for some $t$ between $0$ and $x$. As long as $0 \leq x \leq \pi$, we have $0 < t < \pi$ and so $\sin t > 0$.
<!--ID: 1740583153228-->
