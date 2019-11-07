# Leveraging Gene Co-expression Patterns to Infer Trait-Relevant Tissues in Genome-wide Association Studies

## DOI

https://doi.org/10.1101/705129

## Journal

biorxiv

## Problem
- Tissue specific gene-level annotation / information integrated to GWAS is of interest, eg RolyPoly.
- But previous studies ignore gene coregulations and levels of network activities in genes.

## Method

CoCoNet (for composite likelihood co-expression)

- Y = GWAS gene-level effect size (via local heritability), X = gene expression adjacency matrix, tissue specific using PANDA or some existing tools, is a binary matrix for presence of connectivity; **test if tissue is relevant to disease and cell types**
- Y is generated from A: $MVN(\mu, \Sigma(A))$ --- where for each pair of $\sigma_k * A^(k)$ is variance times correlatoin. $k$ denotes "power" of connectivity.
- Composite likelihood covariance regression --- consider a pair at a time to overcome the computational challenging fitting the MLE for model above.

## Result

- Applied to neurology and immunology GWAS
- Using GTEx data
- Validate with [RISmed](https://cran.r-project.org/web/packages/RISmed/index.html) identified trait-tissue pairs in pubmed title and abstracts.

## Comment

- Other types of network, eg, protein, can also help?

## KW

Xiang Zhou, co-expression, tissue specific
