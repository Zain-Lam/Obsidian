2025-01-09 13:17
Status: 
Tags: [[First Theorems and Notation in Alg 1]] [[a to the n group theorem]]
# a^ma^n equals a^m+n

TD: YEAR1::TERM1::MA151 Algebra 1::04 First Theorems and Notation
Q: Let $G$ be a group, and let $a ∈ G$ then prove $a^{m}a^{n}=a^{m+n}$
?
A:If $m$ and $n$ are positive integers then $$
a^m a^n = \underbrace{a a \cdots a}_{m \text{ times}} \underbrace{a a \cdots a}_{n \text{ times}} = a^{m+n}.
$$If $m$ is positive and $n$ is negative then, since $n = -k$ where $k = -n$ is a positive integer we have$$
a^m a^n = a^m a^{-k} = a^m (a^{-1})^k = \underbrace{a a \cdots a}_{m \text{ times}} \underbrace{a^{-1} a^{-1} \cdots a^{-1}}_{k \text{ times}} = a^{m-k} = a^{m+n}.
$$
Again, the other cases are similar.
<!--ID: 1736930039229-->
