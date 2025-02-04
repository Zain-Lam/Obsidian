2025-02-03 13:18
Status: 
Tags: [[Partial Differentiation and Applications]] [[partial differentiation chain rule for 3 variables]]
# partial differentiation chain rule example

TD: YEAR1::TERM2::MA144 Modelling 2::03 Partial Differentiation and applications
Q: Let $w = xy + yz + zx$, where $x = r\cos\theta$, $y = r\sin\theta$, $z = r\theta$.  
Find $\frac{\partial w}{\partial r}$ using the Chain Rule.
A: Since $x,y,z$ are in terms of $r$ and $\theta$, this just means we need partials for $x,y,z$ in terms of $r$ $$
\frac{\partial w}{\partial r} = \frac{\partial w}{\partial x} \frac{\partial x}{\partial r} + \frac{\partial w}{\partial y} \frac{\partial y}{\partial r} + \frac{\partial w}{\partial z} \frac{\partial z}{\partial r}
$$
which after some working comes to $$
\frac{\partial w}{\partial r} = 2r \left( \cos\theta \sin\theta + \theta (\sin\theta + \cos\theta) \right)
$$
<!--ID: 1738589051615-->

