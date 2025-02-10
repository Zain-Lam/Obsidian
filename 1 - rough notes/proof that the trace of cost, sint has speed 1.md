2025-02-10 13:23
Status: 
Tags: [[Power Series II]]
# proof that the trace of cost, sint has speed 1

TD: YEAR1::TERM2::MA139 Analysis 2::03 Power Series II
Q: Prove that the trace of the circle happens at a rate 1
A: We want to show that $L(t) = t$ for each $t$. By the MVT it suffices to show  
that $L'(t) = 1$ at each point. Consider the point $(\cos t, \sin t)$ and a nearby point $(\cos(t + h), \sin(t + h))$. When $h$ is very small, the (straight line) distance between these two points is approximately the same as the length of the circular arc between them.
So our aim is to show that $$\lim_{h \to 0^+} \frac{1}{h} \sqrt{(\cos(t + h) - \cos t)^2 + (\sin(t + h) - \sin t)^2} = 1$$for every $t$.$$
\begin{align*}
&\lim_{h \to 0^+} \frac{1}{h} \sqrt{(\cos(t + h) - \cos t)^2 + (\sin(t + h) - \sin t)^2} \\
&= \lim_{h \to 0^+} \sqrt{\left( \frac{\cos(t + h) - \cos t}{h} \right)^2 + \left( \frac{\sin(t + h) - \sin t}{h} \right)^2} \\
&= \sqrt{\left( \lim_{h \to 0^+} \frac{\cos(t + h) - \cos t}{h} \right)^2 + \left( \lim_{h \to 0^+} \frac{\sin(t + h) - \sin t}{h} \right)^2} \\
&= \sqrt{(-\sin t)^2 + (\cos t)^2} = 1.
\end{align*}
$$
<!--ID: 1739194268072-->

