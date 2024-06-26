# Longest Alternating Subarray


Your task is to program an algorithm that, for an array of $n$ distinct integers between $1$ and $n$, computes the length of its longest alternating subsequence (i.e., the elements are not necessarily consecutive). A subsequence is called alternating if its values form a zig-zag pattern. More precisely, for a subsequence, write down comparison signs ($<$ and $>$) between its elements. Then, the subsequence is called alternating if the comparison signs form a sequence $(<, >, <, >, ...)$ or $(>, <, >, <, ...)$.

To illustrate, consider the subsequence $(1, 5, 3, 4, 2, 6)$. Then the comparison signs are $(<, >, <, >, <)$, so the subsequence is alternating. On the other hand, consider the subsequence $(1, 5, 3, 4, 6, 2)$. Then the comparison signs are $(<, >, <, <, >)$, so the subsequence is not alternating.

As a final example, for the array $(1, 9, 2, 3, 5, 4, 6, 7, 8)$, the longest alternating subsequence has length $6$ and a corresponding alternating subsequence is $(1, 9, 2, 5, 4, 6)$.

The task is to implement the method longest_alternating_subsequence. You are free to create auxiliary methods. You do not need to change other methods. 

You get one point for each passing test set. To pass both test sets correctly, your solution is expected to run in $O(n^2)$ time, where $n$ is the length of the input array. **Challenge**: try to solve this problem in $O(n \log n)$ or $O(n)$ time.

**Attention**: The index of an array in the code template starts at **0** following the convention of Java.
