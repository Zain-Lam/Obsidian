2025-02-07 13:08
Status: 
Tags: [[Geometry and applications]]
# using hessian example 1

TD: YEAR1::TERM2::MA144 Modelling 2::04 Geometry and Applications
Q: Find and classify the critical points of $f(x, y) = 3y^2 + 2y^3 + 3x^2 + 6xy$.
If $x, y > 0$, obtain the maximum possible value of $f(x, y)$.
A: First we see when $f_{x}=f_{y}=0$
$$
\begin{align}
    f_{x} &= -6 + 6y = 0 & \Rightarrow x &= y \\
    f_{y} &= 6y - 6y^{2} + 6x = 0 & \Rightarrow 6y^{2} &= 12y
\end{align}
$$So we can see the critical points are at $(0,0)$ and $(2,2)$.
To classify we use the determinant of the Hessian which is $72(y-1)$
At $(0,0)$, $D=-72<0\Rightarrow$ a saddle point
At $(2,2)$, $D=72>0$ and $f(x x)<0\Rightarrow$ a local maximum point.
So the maximum in the first quadrant is $f(2,2,)=8$
<!--ID: 1738934604498-->
