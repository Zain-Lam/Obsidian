2025-01-13 19:53
Status: 
Tags: [[Power Series]]
# radius of convergence proof 2

TD: YEAR1::TERM2::MA139 Analysis 2::01 Power Series 1
Q: Prove the radius of convergence pt 2.
?
A:Obviously the series does converge if $x = 0$.
If the series doesn't only converge for $x=0$, it converges for some other values of $x$.
The set of $x$ for which it converges might be unbounded so, it might contain arbitrarily large numbers. In that case the power series will converge absolutely $\forall x \in \mathbb{R}$ and defines a function on $\mathbb{R}$. Otherwise the setis bounded. In that case we let $R = \sup\left\{ |t| : \sum a_n t^n \text{ converges} \right\}$.
Then by our previous theorem the series converges absolutely whenever $|x| < R$. It does not converge if $|x| > R$ by definition of $R$.
<!--ID: 1736798369623-->
