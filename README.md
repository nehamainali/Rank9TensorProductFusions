# Rank9TensorProductFusions
GAP code that checks for nontrivial fusions for the Rank 9 tensor product scheme on a SRG.
This code is executed on GAP (version 4.11).
On GAP prompt (gap>) execute each line of code sequentially.
The code also displays the expected output after execution.
## Theoretical Background
This project is in continuation with the Generalized Hamming scheme project. 
We get fusions only for the SRGs families discussed earlier. These special case fusions are listed and available to view.
## Big Data
We can verify this result with the file that includes all possible fusions of a Rank 9 tensor product scheme. There are more than 4500 partitions to check.
The code uses a set U, which lists all polynomial conditions on eigenvalues that are not feasible, to sieve out partitions that cannot lead to a fusion.
