2025-01-19 16:20
Status: 
Tags: [[DM2 Bubble Sort]]
# bubble sort array sorted proof

TD: YEAR1::TERM2::CS147 Discrete Maths 2::03
Q: Prove that if there is no pair of consecutive entries out of order after using bubble sort, then the entire array is sorted
A: 1) after the $i^{th}$ iteration in the outer loop, $A[n], A[n − 1], · · · , A[n − i + 1]$ are sorted.
2) according to the condition, after the $i^{th}$ iteration, no swap for $A[j]$ with $j = 1, 2, · · · , n − i$,
3) i.e., $A[1], A[2], · · · , A[n − i], A[n − i + 1]$ are sorted.
4) Accordingly, we finish the proof.