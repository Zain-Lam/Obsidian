2025-01-29 17:46
Status: 
Tags: [[Power Series]]
# proof that the exponential increases

TD: YEAR1::TERM2::MA139 Analysis 2::01 Power Series 1
Q: Prove that the exponential function is strictly increasing with a range of $(0,\infty)$
?
A:If we have $x < y$. Then
$$
e^y = e^{y-x} e^x \geq (1 + y - x)e^x > e^x.
$$
This shows that the exponential is strictly increasing.
Since $e^x \geq 1 + x$, the exponential takes arbitrarily large values (at large $x$). Since $e^{-x} = \frac{1}{e^x}$ the exponential also takes values arbitrarily close to $0$ (at large negative $x$).
By the IVT, the exponential takes all positive values.
<!--ID: 1738172953285-->
