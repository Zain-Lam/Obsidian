2025-02-07 10:54
Status: 
Tags: [[Geometry and applications]]
# normal to a surface example 2

TD: YEAR1::TERM2::MA144 Modelling 2::04 Geometry and Applications
Q: Consider the surface defined by $z = x + 2 \sin(x + y)$.
Find the upward-pointing unit normal to the surface at the origin.
Hence, write down the equation of the tangent plane to the surface at the origin.
A: let $G(x,y,z)=x+2\sin(x+y)-z$, then the surface corresponds to $G=0$
and since we know "$\nabla G$ is normal to $G=$ constant" we work out the grad function at the origin$$
\begin{align}
\nabla G&=\begin{pmatrix}
1+2\cos(x+y) \\
2\cos (x+y) \\
-1
\end{pmatrix} \\
\\
\nabla G_{(0,0,0)}&=\begin{pmatrix}
3 \\
2  \\
-1
\end{pmatrix}
\end{align}
$$but this is a normal that points downwards. So $$
\hat{\mathbf{n}}=\frac{1}{\sqrt{ 14 }}\begin{pmatrix}
-3 \\
-2 \\
1
\end{pmatrix}
$$and an example of a tangent plane is $3x+2y-z=0$
<!--ID: 1738926307805-->

