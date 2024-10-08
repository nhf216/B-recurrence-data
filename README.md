# B-recurrence-data
This repository contains supplemental data regarding the sequences $B_{\bar N}$ defined by the recurrence $B_{\bar N}(n)=B_{\bar N}(n-B_{\bar N}(n-1))+B_{\bar N}(n-B_{\bar N}(n-2))+B_{\bar N}(n-B_{\bar N}(n-3))$ and the initial conditions $B_{\bar N}(n)=0$ for $n\leq0$ and $B_{\bar N}(n)=n$ for $1\leq n\leq N$. The behaviors of these sequences for sufficiently large $N$ are completely determined by the congruence class of $N$ mod $7$. The files with names of the form `terms#.pdf` in this repository, one per congruence class, show computation of all terms after Theorem 2 in the paper *The Behavior of a Three-Term Hofstadter-Line Recurrence with Linear Initial Conditions* stops applying. Each calculation is also annotated with a bound on $N$ for which that calculation is valid. The other PDF files are as follows:
* BNterms.pdf: The first 24 terms of $B_{\bar N}$ for all sufficiently large $N$
* BNbarterms.pdf: Terms 25 through 69 of $B_{\bar N}$ for all sufficiently large $N$.

Code for generating sequences and verifying proofs in the paper can be found in the file `Brec.py`. Examples of how to use this code are available in `Brec.ipynb`.
