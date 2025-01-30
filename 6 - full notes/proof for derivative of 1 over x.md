2025-01-30 16:28
Status: 
Tags: [[Limits of functions and the derivative]]
# proof for derivative of 1/x

TD: YEAR1::TERM2::MA139 Analysis 2::02 Limits and the derivative
Q: Prove the derivative of the function $f(x)=\frac{1}{x}$
A: For every $c \neq 0$ and $h$ satisfying $0 < |h| < |c|$, (to rule out the possibility that $h=-c$ because we would be evaluating the function at $x=0$) 
$$
\frac{f(c + h) - f(c)}{h} = \frac{\frac{1}{c + h} - \frac{1}{c}}{h} = \frac{c - (c + h)}{h(c + h)c} = \frac{-h}{h(c + h)c} = \frac{-1}{(c + h)c}
$$  
and so  
$$
\lim_{h \to 0} \frac{f(c + h) - f(c)}{h} = \lim_{h \to 0} \frac{-1}{(c + h)c} = \frac{-1}{c^2}.
$$
as required.
<!--ID: 1738255072064-->
