2025-01-30 16:24
Status: 
Tags: [[Limits of functions and the derivative]]
# proof for derivative of x^2

TD: YEAR1::TERM2::MA139 Analysis 2::02 Limits and the derivative
Q: Prove the derivative for the function $f(x)=x^{2}$.
A: For every $c$ and $h \neq 0$  
$$
\frac{f(c + h) - f(c)}{h} = \frac{(c + h)^2 - c^2}{h} = \frac{c^2 + 2ch + h^2 - c^2}{h} = \frac{2ch + h^2}{h} = 2c + h
$$
and so  
$$
\lim_{h \to 0} \frac{f(c + h) - f(c)}{h} = \lim_{h \to 0} (2c + h) = 2c.
$$
as required.
<!--ID: 1738254396247-->
