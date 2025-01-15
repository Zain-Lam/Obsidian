2025-01-15 10:15
Status: 
Tags: [[The order of an element]]
# finite order element divisibility for identity

TD: YEAR1::TERM1::MA151 Algebra 1::05 The order of an element
Q: Let $m$ be a __non-zero__ integer, then prove that $g^{m}=1 \iff g$ has finite order $d$ with $d |m$.
A: Suppose $g^{m}=1$ where $m$ is a __non-zero__ integer, then $g^{|m|}=1$ and $|m|$ is a positive integer, so $g$ has finite order, which we denote by $d$. By the division algorithm,$$
m=qd+r, \quad q,r\in \mathbb{Z},0\leq r<d
$$Now $g^{d}=1$ by the definition of order, so $1=g^{m}=(g^{d})^{q}\cdot g^{r}=g^{r}$, since $d$ is the __least positive__ integer where $g^{d}=1$, $g^{r}$ is possible with $0\leq r<d\iff r=0$, which implies $m=qd$ which is the same as $d|m$,
For the other way, suppose $g$ has order $d$, and $d|m$, then $g^{d}=1$ and $m=qd$ for some integer $q$.
$g^{m}=(g^{d})^{q}=1$ as required.
<!--ID: 1736937106523-->
