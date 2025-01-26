2025-01-26 14:23
Status: 
Tags: [[Power Series]]
# proof for continuity of power series

TD: YEAR1::TERM2::MA139 Analysis 2::01 Power Series 1
Q: Prove the continuity of power series theorem
A: Suppose $−R < x < R$. WTS that the function is cts at $x$.
Choose $T$ with $|x| < T < R$. Then the series $\sum |a_{n}|T^{n}$ converges, so for each ε > 0 there is some number N for which X∞ N+1 |an| T n < ε/3. Now if |y − x| < T − |x| we will have |y| < T as well as |x| < T. Hence X∞ N+1 |an| |x| n < ε/3 and X∞ N+1 |an| |y| n < ε/3. The partial sum PN 0 an y n is a polynomial in y and polynomials are continuous so there is some δ0 > 0 with the property that if |y − x| < δ0      X N 0 an y n − X N 0 an x n      < ε/3. Therefore if we choose δ to be the smaller of δ0 and T − |x| then if |y − x| < δ we get      X∞ 0 an y n − X∞ 0 an x n      ≤      X∞ N+1 an y n      +      X N 0 an y n − X N 0 an x n      +      X∞ N+1 an x n      7 ≤ X∞ N+1 |an| |y| n +      X N 0 an y n − X N 0 an x n      + X∞ N+1 |an| |x| n < ε.