# FBAT

## DOI

`10.1002/9780470015902.a0022500.pub2`

## Journal

eLS. John Wiley & Sons

## Problem

A review on TDT and FBAT. Proper family based design can help with the problem of genetic confounding.

## Method

### FBAT overview

FBAT is a generalization of TDT suitable for:

- other family designs -- use transmission to unaffected offspring (not the case-only TDT), missing founders, multigenerational families
- other modes of inheritance (not just additive)
  - though Schaid and Sommer (1996) extends TDT to model dominate and recessive inheritance
- dichotomous, measured and time-to-onset phenotypes
- haplotypes of tightly linked markers

### FBAT method outline

writing the likelihood of $f(G|Y,P,\alpha,\beta)$ where $G$ is offspring genotype, $Y$ is offspring phenotype, $P$ is parental genotype, $\beta$ is effect size, $\alpha$ is nuisance parameters such as $\mu=E(Y)$ under the null (covariates are taken into consideration here).

- under the null, the test distribution is simply $f(G|P)$ not depending on how $Y$ is specified.
- under the alternative the score test depends on choice of $f(Y|G,\alpha,\beta)$.
- A form of score test is given as a covariance between genotype and phenotype, $U=\sum_{offspring}(X-E(X|P))(Y-\mu)$ where $X$ is genotype coding under various models of inheritance.
- TDT is a special case of FBAT.

The paper went on with formal arguments on why such test is robust to population structure.

### GDT test and comparison with FBAT

GDT requires knowledge of underlying allele frequency. The score are similar in analytic form but the variance of the score is different. GDT has to assume HWE within each family, ie, no admixture or inbreeding.

## Result

## Comment

Helps to understand what it is meant by:

- linkage but no association
- association but no linkage
- test for association in the presence of linkage (ie, lack of independence btw transmissions to different children in the same family)

## KW

Family-based association, FBAT, TDT

## Further reading

- GDT, Chen et al 2009
- LMM methods (this paper seems to touch some and describe their relationship but it is not very clear if the authors meant it by LMM)