# Hello-MCMC-Bayesian-analysis
Notes on NUDIX sequence analysis using MrBayes

The principle of parsimony as applied to biology says the phylogenetic tree that requires the fewest evolutionary changes is the one you should assume is correct.
https://www.researchgate.net/figure/12349827_fig1_Figure-6-Parsimony-analysis-of-the-amino-acid-sequences-of-HMG-CoA-reductase-available
http://ib.berkeley.edu/courses/ib200a/labs/ib200a_lab13_consensus.pdf
http://phylo.bio.ku.edu/slides/lab8-Bayesian/mblab.pdf

Okay so Paup is a good program to use in parisomy analysis where you are looking for the "phylogenetic tree that requires the fewest evolutionary changes is the one you should assume is correct." This is useful when you are comparing mutiple trees from different taxa. In my situation I want one tree from the human nudix proteins and MrBayes does the best job of compiling the concensus tree from those sampled becuase it uses the postierior probabilities to build it. "It is much better to use the sumt command in MrBayes, because that will
consider the trees based on their estimated posterior probabilities and will also calculate
branch lengths. "
