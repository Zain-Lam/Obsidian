2025-02-27 16:05
Status: 
Tags: [[Linear maps in linalg]] [[definition of a complement subspace]]
# v = u +u' (vector as sum of subspace and its complement)

TD: YEAR1::TERM2::MA150 Algebra 2::05 Linear Maps
Q: Prove that if  $U'$ is a complement to $U \subset V$, then for every $v \in V$ there exist _unique_ $u \in U$ and $u' \in U'$ so that $v = u + u'$.
A: Such an expression exists since $V=U+U'$, if $v = u_2 + u'_2$ with $u_2 \in U$ and $u'_2 \in U'$ is another, then subtracting the two expressions gives $$U \ni u - u_2 = u'_2 - u' \in U' $$so $u - u_2 = u'_2 - u' = 0_V$, as $U \cap U' = \{0_V\}$, and the two expressions are the same.
<!--ID: 1740672745800-->
