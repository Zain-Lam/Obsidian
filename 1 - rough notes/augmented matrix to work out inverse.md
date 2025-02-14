2025-02-14 16:00
Status: 
Tags: [[Linear Systems and Matrices]]
# augmented matrix to work out inverse

TD: YEAR1::TERM2::MA150 Algebra 2::02 Linear Systems and matrices 
Q: How do you use an augmented matrix to work out the inverse of $A$
A: Form the augmented $n \times 2n$ matrix $(A \mid I_n)$,
reduce $A$ into RREF until we arrive at $(R \mid P)$, for some $P \in \operatorname{Mat}_{n \times n}$, then:
(i) if $R = I_n$ then $A$ is invertible with $A^{-1} = P$;
(ii) if $R \neq I_n$ then $A$ is singular.
<!--ID: 1739549689875-->

