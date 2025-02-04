2025-02-04 07:29
Status: 
Tags: [[Partial Differentiation and Applications]]
# using grad operator example

TD: YEAR1::TERM2::MA144 Modelling 2::03 Partial Differentiation and applications
Q: Consider $f:\mathbb{R}^3 \to \mathbb{R}$ and $g:\mathbb{R} \to \mathbb{R}$ defined by $g(t) = f(\mathbf{r}(t))$, where $\mathbf{r}:\mathbb{R} \to \mathbb{R}^3$ is a parametrised curve in $\mathbb{R}^3$. Show that $g'(t) = \nabla f \cdot \mathbf{r}'(t)$.
A: Remember how to apply the chain rule:$$
g'(t) = \frac{\partial f}{\partial x} \frac{dx}{dt} + \frac{\partial f}{\partial y} \frac{dy}{dt} + \frac{\partial f}{\partial z} \frac{dz}{dt}
$$we can then express this as two vectors being dotted: $$
\begin{pmatrix} \frac{\partial f}{\partial x} \\ \frac{\partial f}{\partial y} \\ \frac{\partial f}{\partial z} \end{pmatrix} \cdot \begin{pmatrix} \frac{dx}{dt} \\ \frac{dy}{dt} \\ \frac{dz}{dt} \end{pmatrix}
$$so it follows that this is $$
\nabla f \cdot \mathbf{r}'(t)
$$as required.
<!--ID: 1738654451644-->



