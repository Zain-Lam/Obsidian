2025-01-08 13:12
Status: 
Tags: [[First Theorems and Notation in Alg 1]] [[a to the n group theorem]]
# a^n in G proof

TD: YEAR1::TERM1::MA151 Algebra 1::04 First Theorems and Notation
Q: Let $G$ be a group, and let $a ∈ G$ then prove $a^n ∈ G\ \forall\ n ∈ \mathbb{Z}$.
A: 1) $n=0$, in this first case $a^0=1\in G$ so this is clearly true.
2) if $n\in \mathbb{N}$, we can prove this by induction. This is clearly true for $n=1$ since $a^1=a\in G$.
Now suppose that $a^k\in G$ for some $k \in \mathbb{Z}^+$, then $a^{k+1}=a^{k}a\in G$ since $a,a^{k}\in G$ and $G$ is closed under the binary operation. It follows by induction that $a^{n}\in G\forall n\in \mathbb{Z}^{+}$
3) Then $\forall n\in \mathbb{Z}^{-}$ we know $a^{n}=(a^{-n})^{-1}$. And we know $a^{-n}\in G$ since $-n$ is positive. So the inverse is in the group. i.e $a^{n}\in G$ for negative n,
4) And together this shows that $a^{n}\in G\forall n\in \mathbb{Z}$.
<!--ID: 1736357111631-->
