2025-01-19 16:08
Status: 
Tags: [[DM2 Bubble Sort]]
# bubble sort largest entry at end proof

TD: YEAR1::TERM2::CS147 Discrete Maths 2::03
Q: Prove that after one pass of the array, the largest entry will be at the end.
A: 1) After 1st comparison, $X := max{A[1], A[2]}, A[2] ← X$.
2) After 2st comparison (and swap), $A[3]$ is the largest one among $A[1], A[2], A[3]$.
3) Assume $A[k]$ is the largest one among ${A[i]}^k _{i=1}$, then in the next comparison between $A[k]$ and $A[k + 1]$, (and swap), $A[k + 1]$ is the largest one among ${A[i]}^{k+1}_{i=1}$ 
4) We finish the proof. □
<!--ID: 1737303554082-->
