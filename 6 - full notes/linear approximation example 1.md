2025-02-04 16:15
Status: 
Tags: [[Geometry and applications]]
# linear approximation example 1

TD: YEAR1::TERM2::MA144 Modelling 2::04 Geometry and Applications
Q: Find the linear approximation of $f(x, y) = 2x^2 + y^2$ near $(x, y) = (1, 1)$.
A: Recall that the linear approx is given by$$
f(x, y) \approx f(1, 1) + \nabla f(1, 1) \cdot \begin{pmatrix} x - 1 \\ y - 1 \end{pmatrix}
$$
The gradient of $f(x, y)$ is:
$$
\nabla f(x, y) = \begin{pmatrix} 4x \\ 2y \end{pmatrix}
$$
Evaluating the gradient at $(1, 1)$:
$$
\nabla f(1, 1) = \begin{pmatrix} 4 \\ 2 \end{pmatrix}
$$
Next, we calculate $f(1, 1)$:
$$
f(1, 1) = 2(1)^2 + (1)^2 = 2 + 1 = 3
$$Thus, the linear approximation is
$$
f(x, y) \approx 4x + 2y - 3
$$
<!--ID: 1738686175101-->

