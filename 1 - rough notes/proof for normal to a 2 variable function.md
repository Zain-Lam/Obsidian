2025-02-07 10:02
Status: 
Tags: [[Geometry and applications]]
# proof for normal to a 2 variable function

TD: YEAR1::TERM2::MA144 Modelling 2::04 Geometry and Applications
Q: Prove that for $F : \mathbb{R}^2 \to \mathbb{R}$, the vector $\mathbf{\nabla} F = (F_x, F_y)$ is normal to the curve $F =$ constant.
A: Consider a point $(x_0, y_0)$ on the curve $F(x, y) =$ constant (a contour, or a level curve). Clearly, the constant equals $F(x_0, y_0)$.  
Suppose we use the variable $t$ to parametrise this level curve so that  
$F(x(t), y(t)) = F(x_0, y_0)$ and let $(x_0, y_0)$ correspond to where $t = 0$. Differentiating the above equation with respect to $t$ and using the Chain Rule, we find $\frac{d}{dt} F(x(t), y(t)) = \frac{\partial F}{\partial x} \frac{dx}{dt} + \frac{\partial F}{\partial y} \frac{dy}{dt} = 0$
If we evaluate this at $(x_{0},y_{0})$ then we get$$
\begin{pmatrix} 
\frac{\partial F}{\partial x} \\
\frac{\partial F}{\partial y} 
\end{pmatrix} \Bigg|_{(x_0, y_0)}
\cdot 
\begin{pmatrix} 
x'(0) \\ 
y'(0) 
\end{pmatrix} = 0.
$$showing that $\nabla F$ is perpendicular to the tangent of the 2d curve
<!--ID: 1738926307818-->

