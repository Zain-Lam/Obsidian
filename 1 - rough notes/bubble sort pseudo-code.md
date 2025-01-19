2025-01-19 15:54
Status: 
Tags: [[DM2 Bubble Sort]]
# bubble sort pseudo-code

TD: YEAR1::TERM2::CS147 Discrete Maths 2::03
Q: What's the pseudo-code for bubble sort?
A: $$ \begin{array}{ll}
1: & \text{for } i = 1 ,\dots, n - 1 \text{ do} \\
2: & \quad \text{for } j = 1,\dots, n - i \text{ do} \\
3: & \quad \quad \text{if } A[j] > A[j + 1] \text{ then} \\
4: & \quad \quad \quad X \leftarrow A[j] \\
5: & \quad \quad \quad A[j] \leftarrow A[j + 1] \\
6: & \quad \quad \quad A[j + 1] \leftarrow X \\
7: & \quad \quad \text{end if} \\
8: & \quad \text{end for} \\
9: & \text{end for}
\end{array}
$$  
<!--ID: 1737302489639-->
