## Phylogeny

In Biology, hierarchical clustering and phylogenetic trees are intimately 
linked. Phylogenetic trees also allow a nice exploration of a catch-22 in 
biological data analysis: to cluster sequences, we need to know which 
positions in them to compare (and how to score differences at those 
positions as numbers), but to know which positions in them to compare, we 
use progressive tree alignment, meaning we first align the 2 closest 
sequences, then add the third closest to that, etc. But how do we know 
what close is when we don’t know which positions to compare? 

To dive into this I made this practical, where you implement 
Needleman-Wunsch pairwise alignment yourself and do progressive tree 
alignment using it, and then look at k-mer methods before using Clustal 
Omega. In the end, it’s a nice detour but the course is difficult as is 
and phylogeny lies squarely outside ML proper. So it’s here if you ever 
want to look at this stuff but that’s all (: 

-Dieter Stoker, 05_03_2023
