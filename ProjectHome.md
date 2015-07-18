This is the core MCMC sampler for the nonparametric sparse factor analysis model presented in

David A. Knowles and Zoubin Ghahramani (2011).
Nonparametric Bayesian Sparse Factor Models with application to Gene Expression modelling.
Annals of Applied Statistics

This is Matlab code: hopefully I'll get round to porting this to R at some point. To checkout the source using svn click on the 'Source' tab above, and follow the instructions there. Otherwise download the tar ball [here](http://cs.stanford.edu/~davidknowles/nsfa.tar.gz).

From the abstract:

A nonparametric Bayesian extension of Factor Analysis (FA) is proposed where observed data Y is modeled as a linear superposition, G, of a potentially infinite number of hidden factors, X. The Indian Buffet Process (IBP) is used as a prior on G to incorporate sparsity and to allow the number of latent features to be inferred. The model's utility for modeling gene expression data is investigated using randomly generated datasets based on a known sparse connectivity matrix for E. Coli, and on three biological datasets of increasing complexity.

Official link is [here](http://projecteuclid.org/DPubS?service=UI&version=1.0&verb=Display&handle=euclid.aoas/1310562732)

The pdf is available [here](http://mlg.eng.cam.ac.uk/pub/pdf/KnoGha11b.pdf)

Bibtex for citation:
```
@article{knowles2011nonparametric,
author = {Knowles, D A and Ghahramani, Z},
journal = {The Annals of Applied Statistics},
number = {2B},
pages = {1534--1552},
publisher = {Institute of Mathematical Statistics},
title = {Nonparametric {B}ayesian sparse factor models with application to gene expression modeling},
volume = {5},
year = {2011}
}
```