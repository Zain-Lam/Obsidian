2025-02-17 12:10
Status: 
Tags: [[Vector Spaces]]
# proof that the ring on polynomials R[x] is not a finite-dimensional vector space

TD: YEAR1::TERM2::MA150 Algebra 2::04 Vector spaces 
Q: Prove that the ring of polynomials $\mathbb{R}[x]$ is not a finite-dimensional vector space.
A: Suppose for contradiction that $f_1, \ldots, f_s \in \mathbb{R}[x]$ is a spanning set.
Denote the degrees of these polynomials by $d_i = \deg f_i$. Since the set $\{d_i \mid i = 1, \ldots, s\}$ is a finite set of integers, it has a largest element:
WLOG $d_s \geq d_i$ for all $i = 1, \ldots, s$. But then $x^{d_s+1}$ cannot be written as a linear combination of $f_1, \ldots, f_s$, and so they cannot have formed a spanning set.
<!--ID: 1739799581409-->
