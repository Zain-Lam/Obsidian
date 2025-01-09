2025-01-09 12:21
Status: 
Tags: [[First Theorems and Notation in Alg 1]] [[a to the n group theorem]]
# a^-n group proof

TD: YEAR1::TERM1::MA151 Algebra 1::04 First Theorems and Notation
Q: Let $G$ be a group, and let $a ∈ G$ then prove if $n ∈ Z$ then $(a ^{-1} ) ^{n} = (a ^{n} ) ^{-1} = a^{-n}$
A: 1) Clearly this is true if $n = 0$ since all three of the expressions are equal to 1
2) If $n\in \mathbb{Z}^{+}$ then $a^n (a^{-1})^n = \underbrace{a a \cdots a}_{n \text{ times}} \underbrace{a^{-1} \cdots a^{-1}}_{n \text{ times}}$ 
Each $a a^{-1}$ in the centre collapses to a 1 and eventually we see that this expression is 1. Therefore it’s true to say that $(a^{-1})^n = (a^n)^{-1}$.
Also $(a^n)^{-1} = a^{-n}$ just by notational definition.
3) If $n\in \mathbb{Z}^{-}$  then $a^n (a^{-1})^n = (a^{-n})^{-1} ((a^{-1})^{-n})^{-1} = (a^{-1})^{-n} a^{-n} = 1$ where the expressions either side of the second and third equals sign are the same by what we have already proved for positive integers. The last equals sign follows in a similar way to above (remembering that \(-n\) is a positive integer).