2025-02-18 12:46
Status: 
Tags: [[Vector Spaces]]
# proof for the sifting lemma by sifting

TD: YEAR1::TERM2::MA150 Algebra 2::04 Vector spaces 
Q: Given a finite dimensional vector space $V\neq \{0_{V}\}$ and a spanning set $\mathcal S=\{v_{1},\dots v_{s}\}$, prove the sifting lemma.
A: WLOG $\mathcal L = \{v_1, \ldots, v_r\}$ for some $r \geq 0$.
We consider the elements $v_{r+1}, \ldots, v_s$ in turn. First set $\mathcal{B} = \mathcal L$; we will adjust it as we go. Suppose we are considering $v_j$ for $r + 1 \leq j \leq s$.
If $v_j$ lies in the span of $\mathcal{B}$, then discard it. 
if $v_j \notin \langle \mathcal{B} \rangle$, then replace $\mathcal{B}$ by $\mathcal{B} \cup \{v_j\}$, which is linearly independent.
If $j < s$, continue with this new $\mathcal{B}$ and consider $v_{j+1}$; if $j = s$ then stop.
The resulting $\mathcal{B}$ is linearly independent by construction, and it spans trivially: each $v_j$ that we discarded was a linear combination of other $v_i \in \mathcal{B}$ (in fact, with $i < j$), so in any linear combination of the elements of $S$, we may substitute for $v_j$ by an expression involving only elements of $\mathcal{B}$.
<!--ID: 1739882926917-->
