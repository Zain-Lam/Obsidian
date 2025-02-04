2025-02-04 15:42
Status: 
Tags: [[Geometry and applications]]
# linear approximation of function with n dimensions

TD: YEAR1::TERM2::MA144 Modelling 2::04 Geometry and Applications
Q: Give the linear approximation of a function $f : \mathbb{R}^n \to \mathbb{R}$ defined by $f(x)$ near $x_0$.
A: $$\begin{align}
f(\mathbf{x}) &\approx f(\mathbf{x}_0) + 
\left.
\begin{pmatrix} 
\frac{\partial f}{\partial x_1} \\ 
\frac{\partial f}{\partial x_2} \\ 
\vdots \\ 
\frac{\partial f}{\partial x_n} 
\end{pmatrix} 
\right|_{\mathbf{x}_0} \cdot (\mathbf{x} - \mathbf{x}_0) \\
&=f(\mathbf{\underline{x}_{0}})+\nabla f\Big|_{\mathbf{\underline{x}_{0}}}\cdot(\mathbf{x} - \mathbf{x}_0)
\end{align}
$$which follows on as expected from the case for 1 and 2 dimensions.
<!--ID: 1738684724831-->

