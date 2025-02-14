2025-02-14 13:32
Status: 
Tags: [[Linear Systems and Matrices]]
# solutions by reading off of the augmented matrix

TD: YEAR1::TERM2::MA150 Algebra 2::02 Linear Systems and matrices 
Q: Let $(A \mid \mathbf{b})$ be a matrix in reduced row echelon form which represents a linear system $A\mathbf{x} = \mathbf{b}$ of $m$ equations in $n$ variables. Then what can we say about solutions to the linear system?
A: 1) The system has no solutions if and only if the last non-zero row of $(A \mid \mathbf{b})$ is $( 0 \quad 0 \quad \cdots \quad 0 \mid 1 )$
2) The system has a unique solution if and only if the non-zero rows of $A$ form the identity matrix $I_n$. In particular, this case is only possible if $m \geq n$.
3) The system has infinitely many solutions if $(A \mid \mathbf{b})$ has as many non-zero rows as $A$, and not every column of $A$ contains a pivot (i.e., a leading 1 of some nonzero row). The set of solutions can be described with $k$ parameters, where $k$ is the number of columns not containing a pivot.
<!--ID: 1739540425209-->

