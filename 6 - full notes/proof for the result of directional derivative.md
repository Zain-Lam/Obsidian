2025-02-04 13:34
Status: 
Tags: [[Partial Differentiation and Applications]]
# proof for the result of directional derivative

TD: YEAR1::TERM2::MA144 Modelling 2::03 Partial Differentiation and applications
Q: Prove the result for the directional derivative
A: By definition $$
D_{\underline{\mathbf{u}}} f (\underline{\mathbf{x}})=\lim_{ t \to 0 } \frac{f(\underline{x}+t \hat{\underline{\mathbf{u}}})-f(\underline{x})}{t} 
$$Then let $g(t)=f(\underline{\mathbf{r}}(t))$ where $\underline{\mathbf{r}}(t)=\underline{\mathbf{x}}+t \underline{\mathbf{\hat{u}}}$, which means $\underline{\mathbf{r}}(t)$ is a parametrised line going through $\underline{\mathbf{x}}$.
Note that $\underline{\mathbf{r}}(0)=\underline{\mathbf{x}},\quad \underline{\mathbf{r}}'(t)=\underline{\mathbf{u}},\quad \underline{\mathbf{r}}'(0)=\underline{\mathbf{u}}$ so we get $$\begin{align}
D_{\underline{\mathbf{u}}} f (\underline{\mathbf{x}})=\lim_{ t \to 0 } \frac{g(t)-g(0)}{t} &=g'(0) \\
&=\nabla f\cdot  \underline{\mathbf{r}}'(0)=\nabla f \cdot  \underline{\mathbf{\hat{u}}}
\end{align}
$$as required.
<!--ID: 1738677349548-->

