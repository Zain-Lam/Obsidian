2025-02-15 21:13
Status: 
Tags: [[Subspaces and Bases of RRn]]
# changing the basis of a vector example in RR2

TD: YEAR1::TERM2::MA150 Algebra 2::03 Subspaces and Bases of R^n 
Q: Consider two bases $\underline{\mathbf{f}}_1 = \begin{pmatrix} 1 \\ 1 \end{pmatrix}$, $\underline{\mathbf{f}}_2 = \begin{pmatrix} 1 \\ -2 \end{pmatrix}$ and $\underline{\mathbf{g}}_1 = \begin{pmatrix} -1 \\ 3 \end{pmatrix}$, $\underline{\mathbf{g}}_2 = \begin{pmatrix} 2 \\ -5 \end{pmatrix}$ of $\mathbb{R}^2$. Suppose  $\underline{\mathbf{w}} = -3\underline{\mathbf{f}}_1 + 7\underline{\mathbf{f}}_2$
What are the coefficients with respect to the basis $\underline{\mathbf{g}}_1, \underline{\mathbf{g}}_2$?
A: We basically have to find the coefficients $\mu_1, \mu_2$ so that $\underline{\mathbf{w}} = \mu_1 \underline{\mathbf{g}}_1 + \mu_2 \underline{\mathbf{g}}_2$
$$ \begin{pmatrix} -1 & 2 \\ 3 & -5 \end{pmatrix}^{-1}
\begin{pmatrix} 1 & 1 \\ 1 & -2 \end{pmatrix} \begin{pmatrix} -3\\ 7\end{pmatrix}= \begin{pmatrix} 5 & 2 \\ 3 & 1 \end{pmatrix} \begin{pmatrix} 4 \\ -17 \end{pmatrix} = \begin{pmatrix} -14 \\ -5 \end{pmatrix} $$
We should check this to be sure, and it works out.
<!--ID: 1739654647272-->
