2025-02-12 15:13
Status: 
Tags: [[Column Vectors in Real to n]]
# proof for triangle inequality for vectors

TD: YEAR1::TERM2::MA150 Algebra 2::01 Column Vectors in Real^n 
Q: Prove the triangle inequality for vectors
A: This is done using bilinearity of scalar product  and the Cauchy Schwartz inequality.
We compute the length-squared of $\underline{\mathbf{v}} + \underline{\mathbf{w}}$:
$$
\begin{align} \| \underline{\mathbf{v}} + \underline{\mathbf{w}} \|^2 &= (\underline{\mathbf{v}} + \underline{\mathbf{w}}) \cdot (\underline{\mathbf{v}} + \underline{\mathbf{w}}) \\ &= \underline{\mathbf{v}} \cdot \underline{\mathbf{v}} + \underline{\mathbf{v}} \cdot \underline{\mathbf{w}} + \underline{\mathbf{w}} \cdot \underline{\mathbf{v}} + \underline{\mathbf{w}} \cdot \underline{\mathbf{w}} \\ &\leq \| \underline{\mathbf{v}} \|^2 + | \underline{\mathbf{v}} \cdot \underline{\mathbf{w}} | + | \underline{\mathbf{w}} \cdot \underline{\mathbf{v}} | + \| \underline{\mathbf{w}} \|^2\\ &\leq \| \underline{\mathbf{v}} \|^2 + 2 \| \underline{\mathbf{v}} \| \| \underline{\mathbf{w}} \| + \| \underline{\mathbf{w}} \|^2 \quad \\ &= (\| \underline{\mathbf{v}} \| + \| \underline{\mathbf{w}} \|)^2. \end{align}$$
Thus, $\| \underline{\mathbf{v}} + \underline{\mathbf{w}} \|^2 \leq (\| \underline{\mathbf{v}} \| + \| \underline{\mathbf{w}} \|)^2$
<!--ID: 1739373648705-->

