# Rank9TensorProductFusions
GAP code that checks for nontrivial fusions for the Rank 9 tensor product scheme on a SRG.
This code is executed on GAP (version 4.11).
On GAP prompt (gap>) execute each line of code sequentially.
The code also displays the expected output after execution.
## Theoretical Background
This project builds upon the Generalized Hamming scheme project. It covers nearly all of the rank 9 fusions, primarily for the SRG families discussed in the Generalized Hamming project, with a few exceptions. These special case fusions are listed and available for viewing.
## Big Data
We can verify this result using the file that includes all possible fusions of a Rank 9 tensor product scheme, which contains over 4100 partitions to examine. We start by creating a set U, which consists of polynomials in SRG parameters that cannot be zero for any partition to yield a feasible fusion. This is because the row equality conditions to satisfy the Bannai-Muzychuk Lemma contradict the eigenvalue and parameter restrictions of the SRGs. The code then uses the set U, which identifies infeasible polynomial conditions on eigenvalues, to filter out partitions that cannot produce a fusion.
